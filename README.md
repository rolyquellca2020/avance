# Avance

En este presente trabajo se realizo un simulador de procesos en java

FCFS (First Come First Served) (Política no preferente) el procesador ejecuta cada proceso hasta que termina; es decir los procesos que entran en cola permanecen así hasta que les toque su ejecución en el orden que entraron salen, se conoce también como primero en entrar, primero en salir (First Input First Output – FlFO), no es una política muy utilizada porque puede monopolizar el procesador

ROUND ROBIN RR(Política Preferente) Consiste en conceder a cada proceso en ejecución una variable de tiempo q (quantum),en la cual transcurrido esta cantidad de tiempo si el proceso no ha terminado se devuelve al final de la cola asignándole así el procesador al siguiente proceso.

SPN el siguiente proceso, el más corto: (política no preferente) esta política toma de la cola de procesos el que necesite menos tiempo de ejecución para realizar su trabajo; esta política puede hacer morir los procesos más largos de inanición.

Planificación el Siguiente con Relación de Respuesta Máxima (HRN)Corrige algunas de las debilidades del SJF, tales como el exceso de perjuicio hacia los procesos (trabajos) largos y el exceso de favoritismo hacia los nuevos trabajos cortos.



