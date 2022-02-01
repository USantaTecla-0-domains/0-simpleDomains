# 4-numbering Systems

## 0-digits

### 0-digits/v0
~~~
Dame un número entero 76
Unidades: 6
Decenas: 7.6
Centenas: 0.76
~~~

### 0-digits/v1
~~~
Dame un número entero 76
El número 76 tiene 2 digitos
~~~

### 0-digits/v2
~~~
**ESTA MAL**
Introduce un número:  76
El número 0 no es palidromo
~~~

### 0-digits/v3
~~~
Dame un número entero:  76
Unidades: 6
Decenas: 7 
Centenas: 0
~~~

## 1-toBinary

### toBinary/v0
~~~
Dame un número decimal:  6
Formato binario:  0000 0000 0000 0000 0000 0000 0000 0110
~~~

### toBinary/v1
~~~
Dame un número decimal:  6
Formato binario de 6:  0000 0000 0000 0000 0000 0000 0000 0110
Formato binario de 6 << 1 (12):  0000 0000 0000 0000 0000 0000 0000 1100 
Formato binario de 6 << 2 (24):  0000 0000 0000 0000 0000 0000 0001 1000 
Formato binario de 6 << 3 (48):  0000 0000 0000 0000 0000 0000 0011 0000 
Formato binario de 6 << 4 (96):  0000 0000 0000 0000 0000 0000 0110 0000 
Formato binario de 6 << 5 (192):  0000 0000 0000 0000 0000 0000 1100 0000
Formato binario de 6 >> 1 (3):  0000 0000 0000 0000 0000 0000 0000 0011  
Formato binario de 6 >> 2 (1):  0000 0000 0000 0000 0000 0000 0000 0001  
Formato binario de 6 >> 3 (0):  0000 0000 0000 0000 0000 0000 0000 0000  
Formato binario de 6 >> 4 (0):  0000 0000 0000 0000 0000 0000 0000 0000  
Formato binario de 6 >> 5 (0):  0000 0000 0000 0000 0000 0000 0000 0000  
Formato binario de 6 >>> 1 (3):  0000 0000 0000 0000 0000 0000 0000 0011 
Formato binario de 6 >>> 2 (1):  0000 0000 0000 0000 0000 0000 0000 0001
Formato binario de 6 >>> 3 (0):  0000 0000 0000 0000 0000 0000 0000 0000
Formato binario de 6 >>> 4 (0):  0000 0000 0000 0000 0000 0000 0000 0000
Formato binario de 6 >>> 5 (0):  0000 0000 0000 0000 0000 0000 0000 0000
~~~

## 2-abacus

### 2-abacus/v0
~~~
[
  '', '', '', '', '',
  '', '', '', '', '' 
]
[
  'CDUCDUCDU', '*********',
  '|||||||||', 'ooooooooo',
  '||||||**|', '*********',
  '******|**', '*******|*',
  '*********', 'CDUCDUCDU' 
]
[
  'CDUCDUCDUCDUCDUCDUCDUCDUCDUCDU',
  '*************************|||||',
  '|||||||||||||||||||||||||*****',
  'oooooooooooooooooooooooooooooo',
  '|||||||||||||||||||||****|****',
  '*********************|****|***',
  '**********************|****|**',
  '***********************|****|*',
  '************************|****|',
  'CDUCDUCDUCDUCDUCDUCDUCDUCDUCDU'
]
3
1
3
1
9
2
9
2
[
  'CDUCDUCDU', '*******||',
  '|||||||**', 'ooooooooo',
  '|||||||**', '*********',
  '*******|*', '********|',
  '*********', 'CDUCDUCDU'
]
[
  'CDUCDUCDUCDUCDUCDUCDUCDUCDUCDU',
  '*************************|||||',
  '|||||||||||||||||||||||||*****',
  'oooooooooooooooooooooooooooooo',
  '||||||||||||||||||||||***|****',
  '**************************|***',
  '**********************|****|**',
  '***********************|****|*',
  '************************|****|',
  'CDUCDUCDUCDUCDUCDUCDUCDUCDUCDU'
]
~~~

## 3-binaryToDecimal

### 3-binaryToDecimal/v0
~~~
El número 1000 binario corresponde con el número 8 decimal
~~~

## 4-decimalToBinary

### 4-decimalToBinary/v0
~~~
Dame un numero?  76
00000000000000000000000001001100
~~~

## 5-romanNumerals

### 5-romanNumerals/v0
~~~
101 en romano: CI
45 en romano: XLV
236 en romano: CCXXXVI
841 en romano: DCCCXLI
~~~
### v2
~~~
El número 841 es DCCCXLI
~~~

