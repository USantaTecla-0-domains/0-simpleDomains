# 5-units

## 0-fraction

### 0-fraction/0-inverse
~~~
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3

La fracción 2/3 invertida es la fracción 3/2
~~~

### 0-fraction/0-1-inverse
* Simplificando la fracción mediante el máximo común divisor (visto en el "Recursividad en la Ciencia" del tema "Patrones" del módulo de Fundamento) 
~~~
Introduce el numerador de la fracción: 3
Introduce el denominador de la fracción: 18

La fracción 3/18 = 1/6 invertida es la fracción 6/1
~~~

~~~
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 5

La fracción 2/5 invertida es la fracción 5/2
~~~

### 0-fraction/1-power
~~~
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3
Introduce un exponente: 4

La fracción 2/3 elevado a 4 es la fracción 16/81
~~~

~~~
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3
Introduce un exponente: 0

La fracción 2/3 elevado a 0 es la fracción 1/1
~~~

### 0-fraction/2-add
~~~
Primera fracción:
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3
Segunda fracción:
Introduce el numerador de la fracción: 3
Introduce el denominador de la fracción: 4

La suma de la fracción 2/3 y la fracción 3/4 es la fracción 17/12
~~~

### 0-fraction/3-substract
~~~
Primera fracción:
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3
Segunda fracción:
Introduce el numerador de la fracción: 3
Introduce el denominador de la fracción: 4

La suma de la fracción 2/3 y la fracción 3/4 es la fracción -1/12
~~~

### 0-fraction/4-multiply
~~~
Primera fracción:
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3
Segunda fracción:
Introduce el numerador de la fracción: 3
Introduce el denominador de la fracción: 4

La suma de la fracción 2/3 y la fracción 3/4 es la fracción 6/12
~~~

### 0-fraction/5-divide
~~~
Primera fracción:
Introduce el numerador de la fracción: 2
Introduce el denominador de la fracción: 3
Segunda fracción:
Introduce el numerador de la fracción: 3
Introduce el denominador de la fracción: 4

La suma de la fracción 2/3 y la fracción 3/4 es la fracción 8/9
~~~

### 0-fraction
~~~
Dame el numerador:  2
Dame el denominador:  3
Dame el numerador:  2
Dame el denominador:  4
Dame el numerador:  2
Dame el denominador:  4
Fracción: (2/3) e inversa: (3/2)
Fracción: (2/4) e inversa: (4/2)
Fracción: (2/4) e inversa: (4/2)
Suma: (5/3)
Producto: (1/6)
Suma sin (2/3): (1/1)
Producto sin (2/3): (1/4)
Suma sin (2/4): (7/6)
Producto sin (2/4): (1/3)
Suma sin (2/4): (7/6)
Producto sin (2/4): (1/3)
~~~

## 1-interval

### 1-interval/0-length
~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 9

La longitud del intervalo [4, 9] es 5
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 4

La longitud del intervalo [4, 4] es 0
~~~

### 1-interval/1-includes
~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 9
Introduce un punto: 2

El intervalo [4, 9] no incluye el punto 2
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 9
Introduce un punto: 5

El intervalo [4, 9] si incluye el punto 5
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 9
Introduce un punto: 9

El intervalo [4, 9] si incluye el punto 9
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 9
Introduce un punto: 12

El intervalo [4, 9] no incluye el punto 12
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 4
Introduce un punto: 4

El intervalo [4, 4] si incluye el punto 4
~~~

### 1-interval/2-scale

* Se mantiene el centro del intervalo dado
~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Introduce un factor de escala positivo: 2

El intervalo [4, 10] con factor de escala 2 es el intervalo [1, 13]
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Introduce un factor de escala positivo: 0.5

El intervalo [4, 10] con factor de escala 0.5 es el intervalo [5.5, 8.5]
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Introduce un factor de escala positivo: 0

El intervalo [4, 10] con factor de escala 0 es el intervalo [7, 7]
~~~

### 1-interval/3-shifted
~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Introduce un factor de desplazamiento: 1

El intervalo [4, 10] con factor de desplazamiento 1 es el intervalo [5, 11]
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Introduce un factor de desplazamiento: -4

El intervalo [4, 10] con factor de desplazamiento -4 es el intervalo [0, 6]
~~~

### 1-interval/4-split
~~~
Dame el mínimo: 2
Dame el máximo: 9
Dame el número de partes: 3
[2.0, 4.333333]
[4.333333, 6.666666]
[6.666666, 8.999999]
~~~

~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Introduce una cantidad positiva de intervalos: 2

El intervalo [4, 10] dividido en 2 intervalos son [4, 7] y [7, 10]
~~~

### 1-interval/5-symetric
~~~
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10

El intervalo [4, 10] simétrico al origen es [-10, -4]
~~~

~~~
Introduce el mínimo del intervalo: -4
Introduce el máximo del intervalo (superior o igual al mínimo): 10

El intervalo [4, 10] simétrico al origen es [-10, 4]
~~~

~~~
Introduce el mínimo del intervalo: -10
Introduce el máximo del intervalo (superior o igual al mínimo): -4

El intervalo [-10, -4] simétrico al origen es [4, 10]
~~~

### 1-interval/6-isIntersected
~~~
Dame el mínimo: 2
Dame el máximo: 5
Dame el mínimo: 3
Dame el máximo: 6
Sí existe intersección entre los intervalos [2.0, 5.0] y [3.0, 6.0]
~~~

~~~
Dame el mínimo: 2
Dame el máximo: 5
Dame el mínimo: 6
Dame el máximo: 9
No existe intersección entre los intervalos [2.0, 5.0] y [6.0, 9.0]
~~~



### 1-interval/7-intersection
~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: -3
Introduce el máximo del intervalo (superior o igual al mínimo): 4

El intervalo [4, 10] intersección con el intervalo [-3, 4] es el intervalo [4, 4]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: -3
Introduce el máximo del intervalo (superior o igual al mínimo): 8

El intervalo [4, 10] intersección con el intervalo [-3, 8] es el intervalo [4, 8]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: 5
Introduce el máximo del intervalo (superior o igual al mínimo): 8

El intervalo [4, 10] intersección con el intervalo [5, 8] es el intervalo [5, 8]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: 5
Introduce el máximo del intervalo (superior o igual al mínimo): 12

El intervalo [4, 10] intersección con el intervalo [5, 12] es el intervalo [5, 10]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: 0
Introduce el máximo del intervalo (superior o igual al mínimo): 100

El intervalo [4, 10] intersección con el intervalo [0, 100] será el intervalo [4, 10]
~~~

### 1-interval/8-union
~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: -3
Introduce el máximo del intervalo (superior o igual al mínimo): 4

El intervalo [4, 10] intersección con el intervalo [-3, 4] será el intervalo [-3, 10]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: -3
Introduce el máximo del intervalo (superior o igual al mínimo): 8

El intervalo [4, 10] intersección con el intervalo [-3, 8] será el intervalo [-3, 10]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: 5
Introduce el máximo del intervalo (superior o igual al mínimo): 8

El intervalo [4, 10] intersección con el intervalo [5, 8] será el intervalo [4, 10]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: 5
Introduce el máximo del intervalo (superior o igual al mínimo): 12

El intervalo [4, 10] intersección con el intervalo [5, 12] será el intervalo [4, 12]
~~~

~~~
Primer intervalo:
Introduce el mínimo del intervalo: 4
Introduce el máximo del intervalo (superior o igual al mínimo): 10
Segundo intervalo:
Introduce el mínimo del intervalo: 0
Introduce el máximo del intervalo (superior o igual al mínimo): 100

El intervalo [4, 10] intersección con el intervalo [0, 100] será el intervalo [0, 100]
~~~

### 1-interval/v0
~~~
Longitud: 104
Punto medio: 52
Desplazado izquierda: 0,104
Desplazado derecha: -104,0
Desplazado central: 52,-52
Desplazado inverso: -100,4
~~~

## 2-coordinate

### 2-coordinate/0-onAxes
~~~
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2

La coordenada (2, 2) no está en ningún eje
~~~

~~~
Dame la abcisa de la coordenada:  0
Dame la ordenada de la coordenada:  2

La coordenada (0, 2) está en el eje de abcisas
~~~

~~~
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  0

La coordenada (0, 2) está en el eje de ordenadas
~~~

~~~
Dame la abcisa de la coordenada:  0
Dame la ordenada de la coordenada:  0

La coordenada (0, 2) está en el eje de abcisas y de ordenadas
~~~

### 2-coordinate/1-quadrant
~~~
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2

La coordenada (2, 2) está en el 1º cuadrante.
~~~

~~~
Dame la abcisa de la coordenada:  -2
Dame la ordenada de la coordenada:  2

La coordenada (-2, 2) está en el 2º cuadrante.
~~~

~~~
Dame la abcisa de la coordenada:  -2
Dame la ordenada de la coordenada:  -2

La coordenada (-2, -2) está en el 3º cuadrante.
~~~

~~~
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  -2

La coordenada (2, -2) está en el 4º cuadrante.
~~~

### 2-coordinate/2-isHorizontal
~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  3
Dame la ordenada de la coordenada:  2

La coordenada origen (2, 2) y la coordenada destino (3, 2) si es un movimiento horizontal 
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  3

La coordenada origen (2, 2) y la coordenada destino (2, 3) no es un movimiento horizontal  
~~~

### 2-coordinate/2-isVertical
~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  3
Dame la ordenada de la coordenada:  2

La coordenada origen (2, 2) y la coordenada destino (3, 2) no es un movimiento vertical 
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  3

La coordenada origen (2, 2) y la coordenada destino (2, 3) si es un movimiento vertical  
~~~

### 2-coordinate/2-isKingMovement
~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  3
Dame la ordenada de la coordenada:  2

La coordenada origen (2, 2) y la coordenada destino (3, 2) si es un movimiento del rey 
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  3

La coordenada origen (2, 2) y la coordenada destino (2, 3) si es un movimiento del rey  
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  1
Dame la ordenada de la coordenada:  3

La coordenada origen (2, 2) y la coordenada destino (1, 3) si es un movimiento del rey  
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  4
Dame la ordenada de la coordenada:  5

La coordenada origen (2, 2) y la coordenada destino (4, 5) no es un movimiento del rey  
~~~

### 2-coordinate/2-isQueenMovement
~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  3
Dame la ordenada de la coordenada:  2

La coordenada origen (2, 2) y la coordenada destino (3, 2) si es un movimiento de la reina 
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  3

La coordenada origen (2, 2) y la coordenada destino (2, 3) si es un movimiento de la reina  
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  1
Dame la ordenada de la coordenada:  3

La coordenada origen (2, 2) y la coordenada destino (1, 3) si es un movimiento de la reina
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  6

La coordenada origen (2, 2) y la coordenada destino (2, 6) si es un movimiento de la reina
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  6
Dame la ordenada de la coordenada:  2

La coordenada origen (2, 2) y la coordenada destino (6, 2) si es un movimiento de la reina
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  5
Dame la ordenada de la coordenada:  5

La coordenada origen (2, 2) y la coordenada destino (5, 5) si es un movimiento de la reina
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  4
Dame la ordenada de la coordenada:  8

La coordenada origen (2, 2) y la coordenada destino (4, 8) no es un movimiento de la reina
~~~

### 2-coordinate/2-isHorseMovement
~~~
Coordenada origen:
Dame la abcisa de la coordenada:  1
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  3
Dame la ordenada de la coordenada:  3

La coordenada origen (1, 2) y la coordenada destino (3, 3) si es un movimiento del caballo 
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  1
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  3

La coordenada origen (1, 2) y la coordenada destino (2, 3) no es un movimiento del caballo  
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  8
Dame la ordenada de la coordenada:  1
Coordenada destino:
Dame la abcisa de la coordenada:  6
Dame la ordenada de la coordenada:  2

La coordenada origen (8, 1) y la coordenada destino (6, 2) si es un movimiento del caballo
~~~

~~~
Coordenada origen:
Dame la abcisa de la coordenada:  2
Dame la ordenada de la coordenada:  2
Coordenada destino:
Dame la abcisa de la coordenada:  4
Dame la ordenada de la coordenada:  8

La coordenada origen (2, 2) y la coordenada destino (4, 8) no es un movimiento del caballo
~~~


### 2-coordinate/v0
~~~
La coordinate (-2, -2) SI está en diagonal, en el 3 cuadrante
La coordinate (-1, -1) SI está en diagonal, en el 3 cuadrante
La coordinate (2,1) NO está en diagonal, en el 3 cuadrante   
La coordinate (1,1) SI está en diagonal, en el 3 cuadrante   
La coordinate (0,0) SI está en diagonal.
La coordinate (1,1) SI está en diagonal.
La coordinate (2,1) NO está en diagonal.
La coordinate (1,1) SI está en diagonal.
La coordinate (0,0) SI está en diagonal.
La coordinate (2,1) NO está en diagonal.
La coordinate (1,1) SI está en diagonal.
La coordinate (1,1) SI está en diagonal.
(0,0)
(1,1)
(2,2)
(3,3)
(4,4)
(5,5)
(6,6)
(7,7)
(8,8)
(9,9)
 *********
**********
**********
**********
**********
**********
**********
**********
**********
**********


**********
* ********
**********
**********
**********
**********
**********
**********
**********
**********


**********
**********
** *******
**********
**********
**********
**********
**********
**********
**********


**********
**********
**********
*** ******
**********
**********
**********
**********
**********
**********


**********
**********
**********
**********
**** *****
**********
**********
**********
**********
**********


**********
**********
**********
**********
**********
***** ****
**********
**********
**********
**********


**********
**********
**********
**********
**********
**********
****** ***
**********
**********
**********


**********
**********
**********
**********
**********
**********
**********
******* **
**********
**********


**********
**********
**********
**********
**********
**********
**********
**********
******** *
**********


**********
**********
**********
**********
**********
**********
**********
**********
**********
*********
~~~

### 2-coordinate/v1
~~~
La coordinate (-2, -2) SI está en diagonal, en el 3 cuadrante
La coordinate (-1, -1) SI está en diagonal, en el 3 cuadrante
La coordinate (2,1) NO está en diagonal, en el 3 cuadrante
La coordinate (1,1) SI está en diagonal, en el 3 cuadrante
~~~

### 2-coordinate/v4
~~~
false
false     
horizontal

true      
true      
false     
vertical  
1
false 
~~~

### 1-quadrants

####  1-quadrants/v0
~~~
Dame la abcisa, x =  2
Dame la ordenada, y =  2
La coordenada (2, 2) está en el 1º cuadrante.
~~~


## 3-date

* Se consideran todos los meses de 30 días

### 3-date/0-valid
~~~
Dame el día: 12
Dame el mes: 12
Dame el año: 12

La fecha 12/12/12 sí es válida
~~~

~~~
Dame el día: 30
Dame el mes: 30
Dame el año: 30

La fecha 30/30/30 no es válida
~~~

~~~
Dame el día: 2022
Dame el mes: 2022
Dame el año: 2022

La fecha 2022/2022/2022 no es válida
~~~

### 3-date/2-previous
~~~
Dame el día: 12
Dame el mes: 12
Dame el año: 12

La fecha 12/12/12 y la siguiente es 11/12/12
~~~

~~~
Dame el día: 1
Dame el mes: 1
Dame el año: 12

La fecha 30/1/12 y la siguiente es 30/12/11
~~~

~~~
Dame el día: 1
Dame el mes: 4
Dame el año: 12

La fecha 1/4/12 y la siguiente es 30/3/12
~~~

### 3-date/v0
~~~
El 20 del 3 de 1968 cae a ultimos invierno.
~~~

### 1-seasonWithPart

### 1-seasonWithPart/v0
* Considerar todos los meses de 30 días
* Las estaciones comienzan: invierno el 21/12; primavera el 21/3; verano el 21/6; otoño el 21/9
* Considerar: "a primeros" los 30 primeros días de la estación; "a mediados" los siguientes 30 días de la estación; "a finales" los últimos 30 días de la estación  
~~~
Escriba un día (1-30):  29
Escriba un mes (1-12):  1
Escriba un año (1-...):  2022
El día 29 del 1 de 2022 cae a mediados de invierno.
~~~

## 4-time

### 4-time/0-add
~~~
Primera duración:
Dame las horas: 12
Dame los minutos: 12
Dame los segundos: 12

Segunda duración:
Dame las horas: 10
Dame los minutos: 10
Dame los segundos: 10

La suma es 22:22:22
~~~

~~~
Dame las horas: 40
Dame los minutos: 40
Dame los segundos: 40

Dame las horas: 30
Dame los minutos: 30
Dame los segundos: 30

La suma es 71:11:10
~~~

