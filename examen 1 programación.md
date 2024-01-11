
# actividad 1 

void decimalBinari(int nombre) {
while (nombre != 0) {
print(nombre%2);
nombre = nombre/2;
}
}



# actividad 2 
void binariDecimal(long binari) {

int numdecimal, numbinari, numtraducido, numsepar, recuento=0; 
print ("introduce un numero binario); 
numbinari = next imput;
for (int i = 0; numdecimal != numtraducido; i++);
numsepar = numbinari /i;
numsepar = numsepar % 2;
double resultado = Math.pow(numsepar, i);
recuento = resultado + recuento;

return recuento;
}

# actividad 3 

static boolean (int 
	return (n%2 == 0);
}

# activdad 4 

static void primersNombresParells (int n) {
for (int i =0; i <= n>; i++) {
if (esParell(i)) {
	print(i);
}
}
}

# activad 5 

int menu () 

System.out.println("Tria una de les següents opcions:");
System.out.println(1. "Decimal a binari");
System.out.println(2. "binari a decimal");
System.out.println((3. "Es parell?")
System.out.println("4. Calcular parells de 0 fins a n")
System.out.println("Sortir")
return = input();
}

# actividad 6 

main() {
int opcio = menu();
while (opcio != 0) {
switch(opcio) {
case 1:
System.out.println(“Introdueix un nombre decimal:”);
int nombre = input();
decimalBinari(nombre);
break;
case 2:
System.out.println(“Introdueix un nombre binari:”);
long nombre = input();
binariDecimal(nombre);
break;
case 3:
System.out.println(“Introdueix un nombre:”);
int nombre = input();
System.out.println(esParell(nombre));
break;
case 4:
System.out.println(“Introdueix un nombre màxim:”);
int nombre = input();
primersNombresParells(nombre);
break;
default:
System.out.println(“El nombre és incorrecte”);
}
opcio = menu();
}
}


# actividad 7 

a)
double volumCilindre(double radi, double longitud) {
return pi * radi^2 * longitud;
}
b)
double volumPrismaRectangular(double c1, double c2, double c3) {
return c1 * c2 * c3;
}

# actividad 8 

main() {
println(“Què hem de transportar? 1. Líquids 2. Sòlids”);
int opcio = input();
while(opcio != 1 || opcio != 2) {
println(“No és una opció vàlida”);
println(“Què hem de transportar? 1. Líquids 2. Sòlids”);
opcio = input();
}
double volum = 0;
if (opcio == 1) {
println(“Què medeix el radi de la cisterna”);
double radi = input();
println(“Què medeix de llarg la cisterna”);
double llarg = input();
volum = volumCilindre(radi, llarg);
} else if (opcio == 2) {
println(“Què medeix el costat 1 del camió”);
double c1 = input();
println(“Què medeix el costat 2 del camió”);
double c2 = input();
println(“Què medeix el costat 3 del camió”);
double c3 = input();
volum = volumPrismaRectangular(c1, c2, c3);
}
println(“Quants metres cúbics hem de transportar?”);
double m3_a_transportar = input();
println(“El tràiler té “ + volum + “ centímetres cúbics”);
double capacitat = volum/1000000;
println(“Hi caben “ + capacitat “ metres cúbics”);
int viatges = (int) m3_a_transportar/capacitat;
viatges++;
println(“Has de fer “ + viatges + “ viatges.”);
}
