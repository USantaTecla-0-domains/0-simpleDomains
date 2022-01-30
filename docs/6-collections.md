# 6-collections

## 0-swap

### v0
~~~
Dame un valor:  76
Dame otro valor:  34
Estos son tus valores:
x = [76]
y = [34]

Estos son tus valores intercambiados:
x = [34]
y = [76]
~~~
- Restricción: las únicas sentencias console.writeln(...); que se pueden escribir son:
```
console.writeln("Estos son tus valores intercambiados:\n" + 
  "x=" + x + "\n" +
  "y=" + y + "\n"); 
```
### v0.1
~~~
**ESTA MAL EL CODIGO**
~~~
### v1
~~~
Dame un valor:  76
Dame otro valor:  34
Dame el último valor:  15
Estos son tus valores:
x=76
y=34
z=15

Estos son tus valores intercambiados:
x=34
y=15
z=76

Estos son tus valores intercambiados:
x=15
y=76
z=34

Estos son tus valores intercambiados:
x=76
y=34
z=15
~~~
- Restricción: las únicas sentencias console.writeln(...); que se pueden escribir son:
```
console.writeln("Estos son tus valores intercambiados:\n" + 
  "x=" + x + "\n" +
  "y=" + y + "\n" +
  "z=" + z + "\n");
```
## 1-histogram

### v0.0
~~~
**EL CODIGO ESTA MAL**
~~~
### v0.1
~~~
**EL CODIGO ESTA MAL**
~~~
## 2-order
### v0
~~~
Valores desordenados :
9
2
5
7
1
3
8
0
4
6
Valores ordenados :
0
1
2
3
4
5
6
7
8
9
~~~

## 3-matrixTranspose

### v0
~~~
Array original: 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25
Array transpuesta: 1,6,11,16,21,2,7,12,17,22,3,8,13,18,23,4,9,14,19,24,5,10,15,20,25
~~~
### v0.1
~~~
**ESTA MAL ES CODIGO**
~~~


## 4-permutations

### v0
~~~
Permutación-0: a b c d e 
Permutación-1: b a c d e  
Permutación-2: c a b d e  
Permutación-3: a c b d e  
Permutación-4: b c a d e  
Permutación-5: c b a d e  
Permutación-6: d b a c e  
Permutación-7: b d a c e  
Permutación-8: a d b c e  
Permutación-9: d a b c e  
Permutación-10: b a d c e 
Permutación-11: a b d c e 
Permutación-12: a c d b e 
Permutación-13: c a d b e 
Permutación-14: d a c b e 
Permutación-15: a d c b e 
Permutación-16: c d a b e 
Permutación-17: d c a b e 
Permutación-18: d c b a e 
Permutación-19: c d b a e 
Permutación-20: b d c a e 
Permutación-21: d b c a e 
Permutación-22: c b d a e 
Permutación-23: b c d a e 
Permutación-24: e c d a b 
Permutación-25: c e d a b 
Permutación-26: d e c a b
Permutación-27: e d c a b
Permutación-28: c d e a b
Permutación-29: d c e a b
Permutación-30: a c e d b
Permutación-31: c a e d b
Permutación-32: e a c d b
Permutación-33: a e c d b
Permutación-34: c e a d b
Permutación-35: e c a d b
Permutación-36: e d a c b
Permutación-37: d e a c b
Permutación-38: a e d c b
Permutación-39: e a d c b
Permutación-40: d a e c b
Permutación-41: a d e c b
Permutación-42: a d c e b
Permutación-43: d a c e b
Permutación-44: c a d e b
Permutación-45: a c d e b
Permutación-46: d c a e b
Permutación-47: c d a e b
Permutación-48: b d a e c
Permutación-49: d b a e c
Permutación-50: a b d e c
Permutación-51: b a d e c
Permutación-52: d a b e c
Permutación-53: a d b e c
Permutación-54: e d b a c
Permutación-55: d e b a c
Permutación-56: b e d a c
Permutación-57: e b d a c
Permutación-58: d b e a c
Permutación-59: b d e a c
Permutación-60: b a e d c
Permutación-61: a b e d c
Permutación-62: e b a d c
Permutación-63: b e a d c
Permutación-64: a e b d c
Permutación-65: e a b d c
Permutación-66: e a d b c
Permutación-67: a e d b c
Permutación-68: d e a b c
Permutación-69: e d a b c
Permutación-70: a d e b c
Permutación-71: d a e b c
Permutación-72: c a e b d
Permutación-73: a c e b d
Permutación-74: e c a b d
Permutación-75: c e a b d
Permutación-76: a e c b d
Permutación-77: e a c b d
Permutación-78: b a c e d
Permutación-79: a b c e d
Permutación-80: c b a e d
Permutación-81: b c a e d
Permutación-82: a c b e d
Permutación-83: c a b e d
Permutación-84: c e b a d
Permutación-85: e c b a d
Permutación-86: b c e a d
Permutación-87: c b e a d
Permutación-88: e b c a d
Permutación-89: b e c a d
Permutación-90: b e a c d
Permutación-91: e b a c d
Permutación-92: a b e c d
Permutación-93: b a e c d
Permutación-94: e a b c d
Permutación-95: a e b c d
Permutación-96: d e b c a
Permutación-97: e d b c a
Permutación-98: b d e c a
Permutación-99: d b e c a
Permutación-100: e b d c a
Permutación-101: b e d c a
Permutación-102: c e d b a
Permutación-103: e c d b a
Permutación-104: d c e b a
Permutación-105: c d e b a
Permutación-106: e d c b a
Permutación-107: d e c b a
Permutación-108: d b c e a
Permutación-109: b d c e a
Permutación-110: c d b e a
Permutación-111: d c b e a
Permutación-112: b c d e a
Permutación-113: c b d e a
Permutación-114: c b e d a
Permutación-115: b c e d a
Permutación-116: e c b d a
Permutación-117: c e b d a
Permutación-118: b e c d a 
Permutación-119: e b c d a
~~~

### v1
~~~
Permutación-0: e  d  c  b  a  
Permutación-1: d  e  c  b  a  
Permutación-2: e  c  d  b  a  
Permutación-3: c  e  d  b  a  
Permutación-4: d  c  e  b  a  
Permutación-5: c  d  e  b  a  
Permutación-6: e  d  b  c  a  
Permutación-7: d  e  b  c  a  
Permutación-8: e  b  d  c  a  
Permutación-9: b  e  d  c  a  
Permutación-10: d  b  e  c  a 
Permutación-11: b  d  e  c  a 
Permutación-12: e  c  b  d  a 
Permutación-13: c  e  b  d  a 
Permutación-14: e  b  c  d  a 
Permutación-15: b  e  c  d  a 
Permutación-16: c  b  e  d  a 
Permutación-17: b  c  e  d  a 
Permutación-18: d  c  b  e  a 
Permutación-19: c  d  b  e  a 
Permutación-20: d  b  c  e  a 
Permutación-21: b  d  c  e  a 
Permutación-22: c  b  d  e  a 
Permutación-23: b  c  d  e  a 
Permutación-24: e  d  c  a  b 
Permutación-25: d  e  c  a  b 
Permutación-26: e  c  d  a  b
Permutación-27: c  e  d  a  b
Permutación-28: d  c  e  a  b
Permutación-29: c  d  e  a  b
Permutación-30: e  d  a  c  b
Permutación-31: d  e  a  c  b
Permutación-32: e  a  d  c  b
Permutación-33: a  e  d  c  b
Permutación-34: d  a  e  c  b
Permutación-35: a  d  e  c  b
Permutación-36: e  c  a  d  b
Permutación-37: c  e  a  d  b
Permutación-38: e  a  c  d  b
Permutación-39: a  e  c  d  b
Permutación-40: c  a  e  d  b
Permutación-41: a  c  e  d  b
Permutación-42: d  c  a  e  b
Permutación-43: c  d  a  e  b
Permutación-44: d  a  c  e  b
Permutación-45: a  d  c  e  b
Permutación-46: c  a  d  e  b
Permutación-47: a  c  d  e  b
Permutación-48: e  d  b  a  c
Permutación-49: d  e  b  a  c
Permutación-50: e  b  d  a  c
Permutación-51: b  e  d  a  c
Permutación-52: d  b  e  a  c
Permutación-53: b  d  e  a  c
Permutación-54: e  d  a  b  c
Permutación-55: d  e  a  b  c
Permutación-56: e  a  d  b  c
Permutación-57: a  e  d  b  c
Permutación-58: d  a  e  b  c
Permutación-59: a  d  e  b  c
Permutación-60: e  b  a  d  c
Permutación-61: b  e  a  d  c
Permutación-62: e  a  b  d  c
Permutación-63: a  e  b  d  c
Permutación-64: b  a  e  d  c
Permutación-65: a  b  e  d  c
Permutación-66: d  b  a  e  c
Permutación-67: b  d  a  e  c
Permutación-68: d  a  b  e  c
Permutación-69: a  d  b  e  c
Permutación-70: b  a  d  e  c
Permutación-71: a  b  d  e  c
Permutación-72: e  c  b  a  d
Permutación-73: c  e  b  a  d
Permutación-74: e  b  c  a  d
Permutación-75: b  e  c  a  d
Permutación-76: c  b  e  a  d
Permutación-77: b  c  e  a  d
Permutación-78: e  c  a  b  d
Permutación-79: c  e  a  b  d
Permutación-80: e  a  c  b  d
Permutación-81: a  e  c  b  d
Permutación-82: c  a  e  b  d
Permutación-83: a  c  e  b  d
Permutación-84: e  b  a  c  d
Permutación-85: b  e  a  c  d
Permutación-86: e  a  b  c  d
Permutación-87: a  e  b  c  d
Permutación-88: b  a  e  c  d
Permutación-89: a  b  e  c  d
Permutación-90: c  b  a  e  d
Permutación-91: b  c  a  e  d
Permutación-92: c  a  b  e  d
Permutación-93: a  c  b  e  d
Permutación-94: b  a  c  e  d
Permutación-95: a  b  c  e  d
Permutación-96: d  c  b  a  e
Permutación-97: c  d  b  a  e
Permutación-98: d  b  c  a  e
Permutación-99: b  d  c  a  e
Permutación-100: c  b  d  a  e
Permutación-101: b  c  d  a  e
Permutación-102: d  c  a  b  e
Permutación-103: c  d  a  b  e
Permutación-104: d  a  c  b  e
Permutación-105: a  d  c  b  e
Permutación-106: c  a  d  b  e
Permutación-107: a  c  d  b  e
Permutación-108: d  b  a  c  e
Permutación-109: b  d  a  c  e
Permutación-110: d  a  b  c  e
Permutación-111: a  d  b  c  e
Permutación-112: b  a  d  c  e
Permutación-113: a  b  d  c  e
Permutación-114: c  b  a  d  e
Permutación-115: b  c  a  d  e
Permutación-116: c  a  b  d  e
Permutación-117: a  c  b  d  e
Permutación-118: b  a  c  d  e
Permutación-119: a  b  c  d  e
~~~

## 5-menu

### v0
~~~
Mayores de mayores
Media de mayores: 0
Menores de mayores
Media: 34.714285714285715
Mayores de menores
Media de menores: 0
Menores de menores
~~~
### v1
~~~
Mayores: 
53
53
54
45
77
Media: 34.714285714285715
Menores: 
23
24
34
23
32
11
3
32
22
~~~

## 6-pendiente-5-combinations

### v0.0
~~~
**Repite codigo 4-permutations**
~~~
### v0.1
~~~
**ESTA MAL EL CODIGO**
~~~

### v0.2
~~~
**Repite codigo 4-permutations**
~~~
