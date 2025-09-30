# Lab-7
Utilizando el microcontrolador STM32F4 (núcleo) y el Cube IDE
Este laboratorio consiste en que el estudiante, mediante el uso de Cube IDE y el
microcontrolador STM32F4, practique el uso de los GPIOs y el lenguaje C.
El objetivo de este laboratorio es implementar rutinas en C que permitan al usuario
aumentar y decrementar un contador de décadas y al cambiar de modo se puedan crear
distintos colores de LUZ con un LED RGB.
Parte A: Contadores de Décadas (30 pts) Entrega en Clase
Implemente una rutina para obtener la lectura de 2 botones, los cuales
aumentarán y decrementarán el valor de un contador de décadas. Recuerde
implementar anti-rebote en su botones.
Parte B: Control de LED RGB (30 pts) Entrega en Clase
Implemente una rutina para obtener la lectura de 2 botones, los cuales
aumentarán y decrementarán el valor de un contador el cual controlará el color de
un LED RGB, a continuación, se encuentra la tabla de valores para el LED RGB.
Contador R G B
0 0 0 0
1 1 0 0
2 1 0 1
3 0 0 1
4 0 1 1
5 0 1 0
6 1 1 0
Parte C: Cambio de Modo (25 pts)
Implemente una rutina en donde con un botón usted pueda elegir el modo de
operación de los dos botones implementados anteriormente. Al cambiar de modo
de operación, el valor de cada contador debe guardarse, entonces al regresar a
este modo la secuencia seguirá en el valor correspondente, NO debe reiniciarse.
Recuerde implementar anti-rebote.
Parte D: Indicador de Modo (15 pts)
Implemente 1 LED que indique el modo de funcionamiento, este debe estar
apagado cuando se opera el contador y encendido cuando se opera el LED RGB.
