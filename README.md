# notite-tapi
Notite pentru TAPI

## Culori 
### Acronime
- RGB -> RVA: rosul verde albastru
- CMYK -> CMGN - albastru-verzui (cyan), rosu-purpuriu (magneta), galben, negru
- HSL -> TSL: tenta/nutante saturatie luminozitate
- ROGVAIV: roșu, oranj, galben, verde, albastru, indigo și violet
### Culori comune
- Alb: #FFFFFF , (255, 255, 255)
- Negru: #000000, (0, 0, 0)

- Rosu: #FF0000, (255, 0, 0)
- Verde: #00FF00, (0, 255, 0)
- Albastru: #0000FF, (0, 0, 255)
- Galben: #FFFF00, (255, 255, 0)
- Oranj: #FF7F00, (255, 127, 0)
- Violet: #7F00FF, 	(127, 0, 255)

- Magenta: #FF00FF, (255, 0, 255)
- Fucsia: #FD3F92, (253, 63, 146)
- Cyan: #00FFFF, (0, 255, 255)

- Indigo: #791CF8, (121, 28, 248)
- Portocaliu: #ED7F10, (237, 127, 16)
- Olive/masliniu: #808000, (154, 185, 115)

### Unelte
- https://www.color-blindness.com/color-name-hue/ - site pentru identificat denumirea la culori
- https://ro.wikipedia.org/wiki/List%C4%83_de_culori
- https://www.w3schools.com/colors/colors_names.asp 

## Filtre

### Liniare - Curs 5

- integrale
	- Median uniform
	- Gaussian
- diferentiale
	- Roberts
- integro-diferentiale
	- Prewitt
	- Sobel
	- Canny
	- Haralick
- detectia capetelor de drum
	- Kirsch
- indepartarea zgomotelor punctuale - salt and pepper
	- filtre the tip Laplace

### Neliniare - Curs 6
- statistice
	- medie
	- median neliniar
	- media extremelor
	- min
	- max
	- $\alpha$-median
	- $\alpha$-complementar
	- range
	- quasi-range
	- dispersion-edge
- medie si putere
	- geometrica
	- armonica
	- contra-armonica
	- putere
## Adaptive - Curs 7
- MMSE
- DW-MTM
- ATF ( $\alpha$-trimmed filter)

## Modificare rezolutiei - Curs 9
#### Cresterea rezolutiei
1. Cresterea rezolutiei prin replicare
	1. Replicare
	2. Netezire
2. Intretesare cu linii si coloane nule
	1. Intretesere
	2. Netezire
#### Reducerea rezolutiei
1. Selectarea intretesuta a informatiei
2. Reducerea selectiva
	1. Mediere
	2. Selectie

##  Transformata Karhunen-Loeve - Curs 10
1. Algoritmul Karhunen-Loeve binar
2. Transformarea Karhunen-Loeve monocroma

## Transformata Fourier - Curs 11
- transformata fourier
- serii fourier
- complex unidimensionala
- imagini digitale monocrome
- fourier inversa
- eliminarea frecventelor inalte/joase 
- filtre liniare
- recunoastere de forme

## Stenografie - Curs 12
### LSB
- forma simpla
- forma extinsa

## Fuzzy - Curs 13
1. Logica adevarului nuantat
2. Utilizare in amelioararea contrastului
	- transformarea liniara
	- transformarea sigmoidala
3. Utilizare in netezirea adaptiva

## SVD - Curs 14
 - Metode de descompunere