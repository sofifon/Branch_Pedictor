# Branch_Pedictor

Este git corresponde a la Tarea 1: Predicción de Saltos del curso IE0521 Estructuras de computadoras digitales II de la Escuela de Ingeniería Eléctrica de la Universidad de Costa Rica.

Está realizado en el I Semestre del 2020 por Sofía Fonseca Muñoz, carné B42634.


Se realizó un simulador de distintos predictores de salto en python3 que permiten obtener métricas de rendimiento utilizando un trace como entrada donde se indica la dirección del salto así como el resultado del mismo.
Los predictores utilizados son los siguientes:
-Predictor bimodal.
-Predictor con historia global.
-Predictor con historia privada.
-Predictor con torneo.


Instrucciones:
Para ejecutar el programa, se debe hacer de la siguiente forma:

gunzip -c branch-trace-gcc.trace.gz | branch -s <#> -b <#> -g <#> -p <#> -o <#>

Donde cada uno de los parámetros corresponden de la siguiente manera
s: Tamaño de la tabla BTH
b: Tipo de predicción
g: Tamaño del registro de predicción global
p: Tamaño de los registros de historia privada
o: Salida de la simulación
