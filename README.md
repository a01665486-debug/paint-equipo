Modificacion de Paint.py
Master: Diego Lemus Mejía, A01665486
Usuario de Git: a01665486-debug
Fork: Yerik Escobar Asprón, A01829079
Usuario de Git: Yeaspron

Descripción del Proyecto:
Esta es una versión modificada de Paint de FreeGames, desarollada en Python con Turtle, añadiremós un color y completaremos tres figuras. 
 
Fuente original: Grant Jenks http://www.grantjenks.com/docs/freegames/paint.html

Funcionalidades:

1. Color nuevo (Diego)(hecho)
2. Dibujar un círculo (Diego)(hecho)
3. Completar el rectángulo (Yerik)(hecho)
4. Completar el triángulo (Yerik)(hecho)

Instrucciones para crear y activar el ambiente:

Ejecuta estos comandos en la terminal macOs o en UbuntuWSL:

~python3 -m venv .venv~
~source .venv/bin/activate~

ESTOS COMANDOS SE EJECUTAN DENTRO DE LA CARPETA DEL PROYECTO

Controles:
Se utiliza la función line(start, end) para dibujar líneas rectas entre dos puntos seleccionados.
* Se activa presionando la tecla l.
* El primer clic establece el punto inicial.
* El segundo clic establece el punto final.

Se implementó la función rectangle(start, end) para dibujar rectángulos utilizando dos puntos como esquinas opuestas.
* Se activa presionando la tecla r.
* El primer clic establece una esquina del rectángulo.
* El segundo clic establece la esquina opuesta.

Presiona K para negro
Presiona W para blanco
presiona G para verde
Presiona B para azul
Presiona R para rojo
Presiona P para morado

Se implementó la función triangle(start, end) para dibujar triángulos utilizando dos puntos.
* Se activa presionando la tecla t.
* El primer clic establece el punto inicial.
* El segundo clic establece el punto final.
* Se unen los tres vértices para formar el triángulo.
