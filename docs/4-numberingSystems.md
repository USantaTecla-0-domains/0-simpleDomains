# 4-numbering Systems

## 0-digits

### 0-digits/v0
~~~
Dame un número entero:  65
Unidades: 5
Decenas: 6
Centenas: 0
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
Damen un número inferior a 16 en binario:  1101
El número 1101 binario corresponde con el número 13 decimal
~~~

### 3-binaryToDecimal/v1
~~~
Damen un número en binario:  1101
El número 1101 binario corresponde con el número 13 decimal
~~~

## 4-decimalToBinary

### 4-decimalToBinary/v0
~~~
Dame un número inferior a 16:  8
Bits: 0001
~~~

### 4-decimalToBinary/v1
~~~
Dame un número decimal:  13
Formato binario:  0000 0000 0000 0000 0000 0000 0000 1101
~~~

### 4-decimalToBinary/v2
~~~
Dame un número decimal:  13
Formato binario de 13:  0000 0000 0000 0000 0000 0000 0000 1101
Formato binario de 13 << 1 (26):  0000 0000 0000 0000 0000 0000 0001 1010 
Formato binario de 13 << 2 (52):  0000 0000 0000 0000 0000 0000 0011 0100 
Formato binario de 13 << 3 (104):  0000 0000 0000 0000 0000 0000 0110 1000
Formato binario de 13 << 4 (208):  0000 0000 0000 0000 0000 0000 1101 0000
Formato binario de 13 << 5 (416):  0000 0000 0000 0000 0000 0001 1010 0000
Formato binario de 13 >> 1 (6):  0000 0000 0000 0000 0000 0000 0000 0110
Formato binario de 13 >> 2 (3):  0000 0000 0000 0000 0000 0000 0000 0011
Formato binario de 13 >> 3 (1):  0000 0000 0000 0000 0000 0000 0000 0001
Formato binario de 13 >> 4 (0):  0000 0000 0000 0000 0000 0000 0000 0000
Formato binario de 13 >> 5 (0):  0000 0000 0000 0000 0000 0000 0000 0000
Formato binario de 13 >>> 1 (6):  0000 0000 0000 0000 0000 0000 0000 0110
Formato binario de 13 >>> 2 (3):  0000 0000 0000 0000 0000 0000 0000 0011
Formato binario de 13 >>> 3 (1):  0000 0000 0000 0000 0000 0000 0000 0001
Formato binario de 13 >>> 4 (0):  0000 0000 0000 0000 0000 0000 0000 0000
Formato binario de 13 >>> 5 (0):  0000 0000 0000 0000 0000 0000 0000 0000
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

