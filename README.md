# Sena-Actividad-3.-Calcular-las-Areas-de-Diferentes-Poligonos
Calcular el Area de un Triangulo, un Trapecio, Un Rombo, un Paralelogramo, un Rectangulo y un Circulo

CALCULO DEL AREA DE UN TRIANGULO:

/* Programa para calcular el área de un triángulo, conociendo la base y la altura*/


#include <iostream>;

using namespace std; 

int main ()
{

//Definiendo las variables//
float A = 0;
float base = 0;
float altura = 0;
float resultado1 = 0;
float resultado2 = 0;

//Pidiendo el ingreso de datos por pantalla//

cout <<"Digite el valor de la base:  "; cin >>base;
cout <<"Digite el valor de altura:  "; cin >>altura;

//Operacion para encontrar el área del triangulo//

A = (base * altura/2);
resultado1 = base * altura;
resultado2 = resultado1 / 2;

//Mostrar los resultados por pantalla//

cout <<"El Area del Triangulo es:    " << A << endl;
cout <<"Programa realizado por Jaidi Gonzalez" << endl;

system ("pause");
return 0;
}

CALCULO DEL AREA DE UN TRAPECIO

/* Programa para calcular el área de un trapecio*/
/*Veo que la formula que tienen en la guia está mal planteada, porque es Base Mayor + base menor, no por. El signo está mal, por lo que voy a 
hacer el ejercicio con la formula matemática correcta*/

#include <iostream>

using namespace std; 

int main ()
{

//Definiendo las variables//
float A = 0;
float Base_mayor = 0;
float base_menor = 0;
float altura = 0;
float resultado1 = 0;
float resultado2 = 0;
float resultado3 = 0;

//Pidiendo el ingreso de datos por pantalla//

cout <<"Digite el valor de la Base_mayor:  "; cin >>Base_mayor;
cout <<"Digite el valor de base_menor:  "; cin >>base_menor;
cout <<"Digite el valor de la altura:  "; cin >>altura;

//Operacion para encontrar el área del trapecio//

A = (Base_mayor + base_menor) * altura / 2;

//Mostrar los resultados por pantalla//

cout <<"El Area del Trapecio es:    " << A << endl;
cout <<"Programa realizado por Jaidi Gonzalez" << endl;

system ("pause");
return 0;
}


CALCULO DEL AREA DE UN ROMBO

/* Programa para calcular el área de un rombo, conociendo el valor de los diagonales*/


#include <iostream>

using namespace std; 

int main ()
{

//Definiendo las variables//
float A = 0;
float Diagonal_mayor = 0;
float diagonal_menor = 0;
float resultado1 = 0;
float resultado2 = 0;

//Pidiendo el ingreso de datos por pantalla//

cout <<"Digite el valor de la Diagonal_mayor:  "; cin >>Diagonal_mayor;
cout <<"Digite el valor de diagonal_menor:  "; cin >>diagonal_menor;

//Operacion para encontrar el área del rombo//

A = (Diagonal_mayor * diagonal_menor/2);
resultado1 = Diagonal_mayor * diagonal_menor;
resultado2 = resultado1 / 2;

//Mostrar los resultados por pantalla//

cout <<"El Area del Rombo es:    " << A << endl;
cout <<"Programa realizado por Jaidi Gonzalez" << endl;

system ("pause");
return 0;
}

CALCULO DEL AREA DE UN RECTANGULO

/* Programa para calcular el área de un rectángulo, conociendo la base y la altura*/


#include <iostream>;

using namespace std; 

int main ()
{

//Definiendo las variables//
float A = 0;
float a = 0;
float b = 0;

//Pidiendo el ingreso de datos por pantalla//

cout <<"Digite el valor de a:  "; cin >>a;
cout <<"Digite el valor de b:  "; cin >>b;

//Operacion para encontrar el área del rectángulo//

A = (a * b);

//Mostrar los resultados por pantalla//

cout <<"El Area del Rectangulo es:    " << A << endl;
cout <<"Programa realizado por Jaidi Gonzalez" << endl;

system ("pause");
return 0;
}

CALCULO DEL AREA DE UN PARALELOGRAMO

/* Programa para calcular el área de un paralelogramo, conociendo la base y la altura*/


#include <iostream>;

using namespace std; 

int main ()
{

//Definiendo las variables//
float A = 0;
float base = 0;
float altura = 0;

//Pidiendo el ingreso de datos por pantalla//

cout <<"Digite el valor de la base:  "; cin >>base;
cout <<"Digite el valor de altura:  "; cin >>altura;

//Operacion para encontrar el área del paralelogramo//

A = (base * altura);

//Mostrar los resultados por pantalla//

cout <<"El Area del Paralelogramo es:    " << A << endl;
cout <<"Programa realizado por Jaidi Gonzalez" << endl;

system ("pause");
return 0;
}

CALCULO DEL AREA DE UN CIRCULO:

/* Programa para calcular el área de un círculo, usando una constante.*/


#include <iostream>;

using namespace std; 

int main ()
{

const float PI = 3.1416; //Defino una constante llamada PI.

//Definiendo las variables//
float A = 0;
float radio = 0;

//Pidiendo el ingreso de datos por pantalla//

cout <<"Digite la longitud del radio:  "; cin >>radio;

//Operacion para encontrar el área del triangulo//

A = PI * (radio * radio);

//Mostrar los resultados por pantalla//

cout <<"El Area del circulo es:    " << A << endl;
cout <<"Programa realizado por Jaidi Gonzalez" << endl;

system ("pause");
return 0;
}
