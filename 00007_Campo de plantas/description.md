Nuevamente llegó el momento de procurarse el alimento, pero esta vez Alex encontró un campo lleno de plantas... algunas comestibles y otras no.

Este campo lo vamos a representar con una fila de un tablero Gobstones, que va a estar llena de ambos tipos de plantas. Tu tarea será crear un procedimiento `RecolectarPlantasEnFila()` que:

* **recorra** la fila completa, la cual obviamente no sabemos qué tan larga es, empezando desde el origen y **hacia el Este**;
* en cada parcela (celda), recolecte la planta comestible **si es que hay alguna**;
* deje en su lugar las plantas no comestibles.

Te facilitamos la función `hayPlantaComestible()` y el procedimiento `RecolectarPlanta()` para que los uses.