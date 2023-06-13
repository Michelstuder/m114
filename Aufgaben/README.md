## Aufgaben gelöst am 16.05.2023:

Siehe Aufgabenstellung [hier](https://gitlab.com/ch-tbz-it/Stud/m114/-/blob/main/A.%20Daten%20codieren/A.1%20Zahlensysteme%2C%20numerische%20Codes/README.md)

### 1.)

|BIN(MSB)|BIN|BIN|BIN(LSB)|DEC|HEX|
|:---|:---|:---|:---|---:|---:|
| 0 | 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 1 | 1 | 1 |
| 0 | 0 | 1 | 0 | 2 | 2 |
| 0 | 0 | 1 | 1 | 3 | 3 |
| 0 | 1 | 0 | 0 | 4 | 4 |
| 0 | 1 | 0 | 1 | 5 | 5 |
| 0 | 1 | 1 | 0 | 6 | 6 |
| 0 | 1 | 1 | 1 | 7 | 7 |
| 1 | 0 | 0 | 0 | 8 | 8 |
| 1 | 0 | 0 | 1 | 9 | 9 |
| 1 | 0 | 1 | 0 | 10| A |
| 1 | 0 | 1 | 1 | 11| B |
| 1 | 1 | 0 | 0 | 12| C |
| 1 | 1 | 0 | 1 | 13| D |
| 1 | 1 | 1 | 0 | 14| E |
| 1 | 1 | 1 | 1 | 15| F |

MSB steht für "Most Significant Bit" (das Bit mit dem höchsten Wert) und LSB steht für "Least Significant Bit" (das Bit mit dem niedrigsten Wert).

### 2, 3, 4.)

| Aufgabe | Dezimalzahl | Binärzahl |
|---------|-------------|-----------|
| 1       | 911         | 111'0011  |
| 2       | 1011'0110   | 182       |
| 3       | 1110'0010'1010'0101 | E2A5      |

### 5.)

| Zahl-A   | Zahl-B   | Resultat  |
|----------|----------|-----------|
| 1101'1001| 0111'0101| 0101'1110 |

### 6.)
Die Bitkombination "1100 0000 . 1010 1000 . 0100 1100 . 1101 0011" entspricht der IPv4-Adresse 192.168.76.211

### 7.)
Die Bitkombination "1011 1110 - 1000 0011 - 1000 0101 - 1101 0101 - 1110 0100 - 1111 1110" entspricht einer MAC-Adresse.

### 9.)

Für die Kabinenzählung des Matterhorn-Express mit 107 Gondeln wird eine Codebreite von mindestens 7 Bits benötigt (2^7 = 128). 
12h * 2800 = 33600 Personen
Für die Anzahl Touristen pro Tag würde eine Codebreite von 16 bit genügen (2^16 = 65536)

### 10.)

## Neue Aufgabenstellung

Siehe Aufgabenstellung [hier](https://gitlab.com/ch-tbz-it/Stud/m114/-/tree/main/A.%20Daten%20codieren/A.2%20Alphanumerische%20Codes%20ASCII%20und%20Unicode#aufgaben-zu-ascii-und-unicode)

### 1.)
Textsample1 - ANSI
Textsample2 - UTF-8
Textsample3 - UTF-16 BE BOM

### 2.)
Textsample 1 besteht aus 68 Zeichen, während die anderen aus 71 Zeichen bestehen.

### 3.)

## Aufgaben gelöst am 30.05.2023

Siehe Aufgabenstellung [hier](https://gitlab.com/ch-tbz-it/Stud/m114/-/tree/main/A.%20Daten%20codieren/A.4%20Bildcodierung#2-farbcodierung-rgb-cmyk)

RGB:
#FF0000 entspricht der Farbe Rot
#00FF00 entspricht der Farbe Grün
#0000FF entspricht der Farbe Blau
#FFFF00 entspricht der Farbe Gelb
#00FFFF entspricht der Farbe Cyan
#FF00FF entspricht der Farbe Magenta
#000000 entspricht der Farbe Schwarz
#FFFFFF entspricht der Farbe Weiß
#00BC00 entspricht der Farbe Dunkelgrün

CMYK:
C:0%, M:100%, Y:100%, K:0% entspricht der Farbe Cyan
C:100%, M:0%, Y:100%, K:0% entspricht der Farbe Magenta
C:100%, M:100%, Y:0%, K:0% entspricht der Farbe Gelb
C:0%, M:0%, Y:100%, K:0% entspricht der Farbe Blau
C:100%, M:0%, Y:0%, K:0% entspricht der Farbe Rot
C:0%, M:100%, Y:0%, K:0% entspricht der Farbe Grün
C:100%, M:100%, Y:100%, K:0% entspricht der Farbe Weiß
C:0%, M:0%, Y:0%, K:100% entspricht der Farbe Schwarz
C:0%, M:0%, Y:0%, K:0% entspricht der Farbe Transparent (keine Farbe)
C:0%, M:46%, Y:38%, K:22% entspricht der Farbe Dunkelgrün

YCbCR:
RGB 255/255/255 ergibt in YCbCr:
Y: 1, Cb: 0, Cr: 0

RGB 0/0/0 ergibt in YCbCr:
RGB 255/255/255 ergibt in YCbCr:
Y: 1, Cb: 0, Cr: 0

RGB 0/0/0 ergibt in YCbCr:
Y: 0, Cb: 0, Cr: 0

Y: 1, Cb: 0, Cr: 0 entspricht der Farbe Rot
Y: 0, Cb: 0, Cr: 0 entspricht der Farbe Schwarz
Y: 0, Cb: 1, Cr: 0 entspricht der Farbe Blau
Y: 0, Cb: -1, Cr: 0 entspricht der Farbe Gelb
Y: 0, Cb: 0, Cr: 1 entspricht der Farbe Rot
Y: 0, Cb: 0, Cr: -1 entspricht der Farbe Cyan

## Neue Aufgabenstellung

Siehe Aufgabenstellung [hier](https://gitlab.com/ch-tbz-it/Stud/m114/-/tree/main/B.%20Daten%20komprimieren/B.1%20Verlustlose%20Komprimierung#aufgaben-zu-komprimierung)


