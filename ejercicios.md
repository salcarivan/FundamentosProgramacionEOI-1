## 1. Calcular y mostrar el cuadrado de los números del 1 al 30.

```
AlgoritmoCalcularCuadrado1_30
Mostrar "Ingrese un número del 1 al 30."
Leer N
Mientras N<30 y N>1 
Mostrar N*n
Fin AlgoritmoCalcularCuadrado1_30
```

<br>

## 2. Numeros primos. 

```
Algoritmo_numeros_primos
Leer N
Div <- 2
Band <- Verdadero
Si nro=1 Entonces
Escribir "Es primo"
Sino
Mientras band=Verdadero y nro>div Hacer
Si nro MOD div = 0 Entonces
band <- Falso
FinSi
div <- div +1
FinMientras
si band=Verdadero Entonces
Escribir "Es primo"
Sino Escribir "No es primo"
Fin Si
Fin si
Fin Algoritmo_numeros_primos
```
<br>


## 3. Construir un avión de papel.

```
Algoritmo_Avion_de_papel
Mostrar "Conseguir hoja de papel."
Mostrar "Doblarla."
Mostrar "Darle forma de avión."
Fin Algoritmo_Avion_de_papel
```
<br>

## 4. Suma, resta, multiplicación y divisi.**

```
Algoritmo_operaciones
Mostrar "Ingrese un número del 1 al 4: 1 = suma, 2 = resta, 3 = multiplicación, 4 = división."
Si n=1
  Mostrar "Ingrese el valor del primer número (a)"
  Leer a
  Mostrar "Ingrese el valor del segundo número (b)"
  Leer b
  suma <- a+b
  Mostrar a+b
Fin si
Si n=2
  Mostrar "Ingrese el valor del primer número (a)"
  Leer a
  Mostrar "Ingrese el valor del segundo número (b)"
  Leer b
  resta <- a-b
  Mostrar a-b
Fin si
Si n=3
  Mostrar "Ingrese el valor del primer número (a)"
  Leer a
  Mostrar "Ingrese el valor del segundo número (b)"
  Leer b
  multiplicacion <- a*b
  Mostrar a*b
Fin si
Si n=4
  Mostrar "Ingrese el valor del primer número (a)"
  Leer a
  Mostrar "Ingrese el valor del segundo número (b)"
  Leer b
  division <- a/b
  Mostrar a/b
Fin si
Si n>4
  Mostrar "Por favor, ingrese un número del 1 al 4."
Fin si
Fin Algoritmo_operaciones
```
## 5. Volumen y área de un cilindro.

```
InicioAlgoritmo volumen_area_cilindro
h = 0
r = 0
v = 0
a = 0
Mostrar "Ingrese la altura."
Leer N (h)
Mostrar "Ingrese el radio."
Leer N (r)
Volumen (v) = 3'14*(r*r)*h
Area (a) = 2*3'14*r(r+h)
Mostrar "El volumen del cilidro es " + v
Mostrar "El área del cilindro es " + a 
FinAlgoritmo volumen_area_cilindro
```
<br>

## 6. Pedir un libro en una biblioteca.

```
```

<br>


## 7. Determinar el mayor de tres números.**

```
InicioAlgoritmo mayorTresNumeros
Escribir "Introduzca tres numeros"
Leer a, b, c
Si a>b y a>c
    Escribir "El número " + a + " es el mayor"
SiNo
    Si b>c
        Escribir "El número " + b + " es el mayor"
    SiNo
        Escribir "El número " + c + " es el mayor"
    FinSi
FinSi
FinAlgoritmo mayorTresNumeros

```
<br>

## 8. Factorial de cualquier número.

```
Algoritmo_factorial
Mostrar "Escriba un número."
Leer n
fact = 1
Mientras n>=1 Entonces
  fact = fact*n
  n = n-1
Fin Mientras
Mostrar "Factorial =" fact
Fin Algoritmo_factorial
```
<br>

## 9.Encontrar si un número es mayor o menor a un número dado."

```
Algoritmo_numero_mayor_menor
Mostrar "Escriba el primer número."
Leer a
Mostrar "Escriba el segundo número."
Leer b
Si a>b
  Mostrar "El número mayor es " + a +  " y el número menor es " + b
SiNo
  Mostrar "El número menor es " + a + " y el número mayor es " + b
FinSi
Fin Algoritmo_numero_mayor_menor
```
<br>

## 10. Advinar una palabra.

```