# MANUAL DE USUARIO — PIEDRA, PAPEL O TIJERA

Proyecto: Piedra, Papel o Tijera — Actividad 7 
Institución: E.E.S.T. N.º 1 “Eduardo Ader” — Vicente López 
Asignatura: Laboratorio de Programación (LPR) — 5.º año
Docentes: Mansilla Muñoz York Elías y Yamil Ganduglia
Autor: Lucas Benitez (Grupo 1)
Fecha: 14 de octubre de 2026 
Versión: v1.0.0 


CONTROL DE VERSIONES 

Versión v1.0.0 
Fecha 14/10/2026 
Autor Lucas Benitez
Descripción Versión inicial del manual del usuario para la Actividad 7. 


1. INTRODUCCIÓN
El programa Piedra, Papel o Tijera es una aplicación de consola desarrollada en C++. Permite al usuario jugar contra la computadora, obtener el resultado de cada partida y consultar un historial de partidas almacenadas en un archivo de texto.
El sistema utiliza un menú principal para facilitar el acceso a sus funciones.

2. REQUISITOS DEL SISTEMA
Para utilizar el programa se necesita:
Una computadora con Windows.
El archivo ejecutable piedrapapelotijera.exe.
Acceso a la carpeta del proyecto para conservar los registros.
Una terminal, como Windows PowerShell, para iniciar el programa.

3. INICIO DEL PROGRAMA
Abrir la carpeta del proyecto piedrapapelotijera.
Abrir una terminal en esa carpeta.
Ejecutar el siguiente comando:
.\src\piedrapapelotijera.exe
Al iniciar, se mostrará el título del juego y el menú principal.

4. FUNCIONAMIENTO DEL MENÚ PRINCIPAL
El programa ofrece tres opciones:

### Opción 1: Jugar partida
Seleccionar la opción 1.
Ingresar el nombre o apodo del jugador.
Elegir una jugada ingresando el número correspondiente:
# 1: Piedra.
# 2: Papel.
# 3: Tijera.
Esperar a que la computadora realice su elección.
Ver el resultado que aparece en pantalla.

### Opción 2: Ver historial de partidas
Seleccionar la opción 2 para visualizar las partidas guardadas en el archivo src/historial_partidas.txt.
El historial muestra el identificador de cada partida, el nombre del jugador, las elecciones realizadas y el resultado obtenido.
Si todavía no existen partidas guardadas, el programa informa esta situación.

### Opción 3: Salir del sistema
Seleccionar la opción 3 para finalizar la ejecución del programa.
Las partidas guardadas permanecen en el archivo de historial, siempre que este no sea eliminado.

5. RECOMENDACIONES DE USO
Ingresar una opción válida del menú.
Seleccionar un número del 1 al 3 al elegir la jugada.
Ejecutar el programa desde la carpeta raíz del proyecto para que la ruta del historial funcione correctamente.
No eliminar el archivo historial_partidas.txt si se desea conservar las partidas anteriores.

6. CONCLUSIÓN
Este programa permite practicar el juego Piedra, Papel o Tijera y consultar los resultados de partidas anteriores. Su sistema de persistencia permite conservar información entre distintas ejecuciones, mientras que su menú facilita el uso de las funciones principales.
