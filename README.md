# Ejercicio memory - React

Vamos a crear un juego de Memory en React.

Cada estudiante crea un repositorio en github llamado memory.

Para empezar, definamos la estructura básica del juego y los componentes necesarios:

Estructura del Juego:
* Tablero: Un componente padre que contiene todas las cartas.
* Carta: Un componente hijo que representa una carta individual.

Comportamiento:
* Cada carta tiene dos estados: boca arriba y boca abajo.
* Al hacer clic en una carta, esta se voltea.
* Si se voltean dos cartas iguales, permanecen boca arriba.
* Si son diferentes, se vuelven a voltear boca abajo después de un breve tiempo.
* El juego termina cuando todas las cartas estén boca arriba.