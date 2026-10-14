Manual del programador — Piedra, Papel o Tijera

1. Descripción general

El proyecto consiste en un juego desarrollado en C++ que permite jugar a Piedra, Papel o Tijera contra la computadora y almacenar el historial de partidas en un archivo de texto.

2. Tecnologías utilizadas

- C++: lenguaje de programación.
- "struct": agrupación de los datos de cada partida.
- "fstream": lectura y escritura de archivos.
- "cstdlib" y "ctime": generación de jugadas aleatorias.

3. Estructura de datos

Se utiliza la estructura "Partida", que contiene:

- "idPartida": identificador de la partida.
- "jugador": nombre o apodo del jugador.
- "eleccionJugador": jugada seleccionada por el usuario.
- "eleccionIA": jugada seleccionada por la computadora.
- "resultado": resultado final.

4. Funciones principales

- "main()": inicializa el programa y muestra el menú.
- "jugarPartida()": gestiona una partida y determina el resultado.
- "guardarEnDisco()": agrega los datos al archivo de historial.
- "leerHistorialDisco()": recupera y muestra las partidas guardadas.

5. Persistencia de datos

Se utiliza "ofstream" con "ios::app" para agregar partidas al archivo "src/historial_partidas.txt" sin sobrescribir los registros anteriores.

Para consultar el historial se utiliza "ifstream", que permite leer los datos almacenados.

6. Compilación

Desde la carpeta raíz del proyecto, ejecutar:

g++ -std=c++11 src/main.cpp -o src/piedrapapelotijera.exe

7. Consideraciones

El archivo de historial debe conservarse para mantener los registros entre ejecuciones. El programa debe ejecutarse desde la carpeta raíz del proyecto para que la ruta relativa del archivo funcione correctamente.