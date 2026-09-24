Processing
IDE
Educativo

No es como pure data 

Es un programa bastante amable

void setup() {}
Setup se define una vez

void draw(){} 
Draw hace el sitio de trabajo

// Que no se tome en cuenta, mensajes escritos que no afectan el código
Cómo citar de quién usaste el código
O que IA usaste

 size tamaño del lienzo
Background color de fondo

Find in reference

Background alpha, transparencia

***COLORES en processing***

Profundidad de color (bits) 8 bits es el estándar

Modelo de color

RGB - Síntesis aditiva de color (Cada uno 8 bits, R=8 G=8 B=8, CYMK es más pesada por lo tanto)
CMYK-síntesis sustractiva de color
Escala de grises

0 es apagado 1 es encendido (software)
(hardware) Transistor apagado ( negro 255) y encendido (blanco)

HSB
Hue Tono
Saturation Saturación
Brightness Brillo
Hexadecimal- FFFFF
Selector de color
Aparece el hexadecimal para elegir y el HSB y el RGB
Hue es en grado

RGB es el predeterminado de processing
colorMode ();
Background(,,,);
Point (); posición, no tamaño, solo es un pixel
stroke(); poner linea con color
line();  x, y , x , y
Ejemplo si quiero que sea a la mitad
line(width/2, height/2, 300, 100);
rectMode(CENTER) centrar el rectángulo
fill(); llenar de color la figura
circle();
figuraMode define desde donde parte el dibujo (circleMode, rectMode, ellipseMode)

El orden importa

VARIABLES
Sirven para descargar el computador y procesos
translate(); mover cosas (numero positivos y negativo)
pushMatrix(); se ocupa con popMatrix();
Se evita que lo que está arriba se rote también, mueve el lienzo completo
rotate(PI/); está en radiales (en Pi)
Con beginShape(); y endShape();
vertex(); dibujo vectorial
Terminar con endShape(CLOSE);
Antes de beginshape se pueden hacer las modificaciones de color 

