# EjerciciosEspai
Ejercicios para el curso de C++


Ejercicios capítulo 4

1. Explica qué es una sentencia, y cómo diferenciamos las simples y las compuestas.

2. Dado el siguiente programa:
#include <iostream>
using namespace std;
int main() {
int x = 7;
int y = 3;
int z = 0;
z = x * y;
cout << "z = " << z;
return 0;
}
a. Explica lo que está sucediendo en z = x * y;
b. ¿Cuál será el resultado de este programa?
c. Indica los operadores de asignación, operadores y operandos que encuentres.

3. ¿Cómo averiguarías si un número es divisible por otro?

4. Toma la variable contador (de tipo entero) e incrementa su valor en 1. Hazlo de 2 maneras
diferentes.

5. ¿Cuál será la salida de este programa?
#include <iostream>
using namespace std;
int main() {
int x = 7;
int y = 7;
cout << "x = " << x++ << endl;
cout << "y = " << ++y << endl;
return 0;}
Explica además el porqué de este resultado.

6. Dado el siguiente programa:
#include <iostream>
using namespace std;
int main() {
bool iguales = false;
int x = 7;
int y = 8;
iguales = (x == y);
cout << "iguales? " << iguales << endl;
return 0;
}
Y su salida
iguales? 0
a. Explica la expresión marcada en amarillo.
b. Cómo harías que el resultado fuera iguales? 1 cambiando una sola letra.

7. Haz un programa que pida dos números al usuario y nos diga cuál es mayor de los 2.

8. Haz un programa que pida 3 números al usuario, y nos diga si el último está entre los dos primeros.

9. Dado el siguiente programa:
#include <iostream>
using namespace std;
int main() {
int x = 7;
if (x > 5 and x < 15)
{
cout << 1 << endl;
}
if (x > 5 or x < 15)
{
cout << 2 << endl;
}
if (!(x > 5) and x < 15)
{
cout << 3 << endl;
}
if (x > 5 or !(x < 15))
{
cout << 4 << endl;
}
if (!(x > 5 and x < 15))
{
cout << 5 << endl;
}
return 0;
}
Escribe cuál será el resultado.

10. Analiza el siguiente código, escribe cual será su salida y explica porqué.
#include <iostream>
using namespace std;
int main() {
int x = 7;
if (x > 5)
{
x = 4;
if (x > 6)
{
cout << 1 << endl;
}
else
{
cout << 2 << endl;
}
}
return 0;
}
¿Y si la primera línea fuera int x = 0; ?
