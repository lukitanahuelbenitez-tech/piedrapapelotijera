Piedra papel o tijera

Información del proyecto

- Materia: Laboratorio de Programación (LPR)
- Curso: 5º3
- Actividad 7 — Laboratorio de Programación (LPR)
- Año: 2026
- Estudiante: Lucas Benitez


Descripción
Este proyecto consiste en desarrollar un juego de Piedra, Papel o Tijera en C++. El usuario juega contra una inteligencia artificial que selecciona una jugada aleatoria.
El programa utiliza una estructura "struct" para organizar los datos de cada partida y archivos de texto para guardar y consultar el historial de resultados.

Objetivos

- Aplicar estructuras de datos mediante "struct".
- Generar elecciones aleatorias para la computadora.
- Utilizar archivos con "fstream" para guardar y leer información.
- Comprender la persistencia de datos en disco.
- Organizar el código fuente y la documentación del proyecto.

Funcionalidades

1. Jugar una partida de Piedra, Papel o Tijera.
2. Consultar el historial de partidas guardadas.
3. Guardar el nombre del jugador, las elecciones y el resultado de cada partida.
4. Salir del programa.

Estructura del proyecto

<pre>
piedrapapelotijera/
├── .gitattributes                  <-- Normalización de finales de línea
├── .gitignore                      <-- Exclusiones (.exe, *.out, .vscode/)
├── LICENSE                         <-- Licencia MIT escolar
├── README.md                       <-- Portada del proyecto con integrantes
├── docs/                           <-- Entregables y documentación
│   ├── InformeEEST1_LPR2026_ACT07_G03_Informe_v1.0.0.pdf 	<-- Informe APA v7
│   └── CHANGELOG.md                <-- Historial de versiones del software
│   └── manuales                
│   	├── manual_programador_v1.0.0.pdf
│   	├── manual_programador_v1.0.0.md
│   	├── manual_usuario_v1.0.0.pdf
│   	├── manual_usuario_v1.0.0.md
├── src/                            <-- Código fuente compilable
│   ├── main.cpp                    <-- Programa principal del juego en C++
│   └── historial_partidas.txt     <-- Archivo de persistencia generado
└── capturas/                       <-- Evidencias de ejecución (.png)
    ├── jugada_consola.png          <-- Captura del menú y partida jugada
    └── archivo_disco.png           <-- Captura del archivo .txt abierto
</pre>

El archivo "historial_partidas.txt" se genera al guardar la primera partida y se encuentra dentro de "src/".


Compilación y ejecución

Desde la carpeta raíz del proyecto, ejecutar:

g++ -std=c++11 src/main.cpp -o src/piedrapapelotijera.exe

Luego ejecutar:

.\src\piedrapapelotijera.exe


Autor

Nombre y apellido: Lucas Benitez


Licencia

Este proyecto utiliza la licencia MIT con fines educativos.