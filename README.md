# CancerDynamic_GameTheory
Modelo de Teoría de Juegos de la Dinámica del Cáncer con Cuatro Fenotipos Celulares


-Para el código "proyecto.py", seguir: 

1. Abrir
2. Ejecutar por bloques


No se requieren entradas del usuario.

El resultado del código son:
	-Tablas generadas en cada iteración por el método simplex
	-Vector solución x
	-Valor Óptimo z
	-Un ejemplo del método gráfico (alternativo para dos variables)

Se pueden modificar los parámetros del modelo en el primer bloque. 

El código tiene una clase de funciones llamada "ModeloLineal()" la cual crea la tabla correspondiente que utiliza el método simplex. Los datos de entrada son 
-Matriz de pagos A
-Vector de coeficientes libres b
-Vector de coeficientes de desigualdades c

Un ejemplo del uso de la clase "ModeloLineal" es:
	model1 = ModeloLineal()
Para añadir los datos se usa:
	model1.addA(A)
	model1.addB(b)
	model1.addC(c)


Autora
Erika Rivadeneira Pérez - Matemáticas Aplicadas CIMAT
