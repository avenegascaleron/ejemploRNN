# Generación de nombres usando Redes Neuronales Recurrentes

Código fuente en donde se muestra cómo usar una simple arquitectura de Red Neuronal Recurrente (RNN) para generar apellidos vascos.

El set de entrenamiento contiene 18117 apellidos vascos. El modelo se implementa en Keras a partir de una celda recurrente (SimpleRNN), y el entrenamiento y generación de nombres se lleva a cabo caracter por caracter.

Tras 10000 iteraciones de entrenamiento se obtienen nombres generados como estos:

- *Litzay*
- *Oate*
- *Oymea*
- *Girtxa*
- *Etechoilo*
- *Gedikare*
- *Utenmenga*
- *Chalenbibaga*


## Dependencias
Keras==2.2.4
numpy==1.16.3