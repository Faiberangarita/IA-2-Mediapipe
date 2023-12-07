# Proyecto de IA-2 para la predicción de puntos clave del rostro con OpenPose

## Autores del proyecto
Faiber Stiven Angarita Mendoza

## Objetivo
El objetivo de este proyecto es identificar los puntos clave del rostro para cada paciente y clasificarlo como Parkinson o Control.

## Dataset

El dataset está compuesto por dos clases de pacientes: Control (7 pacientes) y Parkinson (7 pacientes), lo que suma un total de 14 pacientes. Cada paciente en el dataset realiza las siguientes acciones:

- Pronuncia 3 veces las vocales (A, E, I, O, U).
- Repite 9 veces una palabra, separándola por sílabas. Por ejemplo: PE-TA-KA.
- Recita 54 palabras, como "Agarrar" o "Hospital".

Cada paciente es grabado en video mientras realiza estas actividades, dando como resultado un total de 924 videos.

## Descripción del proyecto

Nuestro proyecto tiene como objetivo desarrollar un modelo preciso y confiable capaz de predecir, con un alto grado de confianza, si un paciente presenta los movimientos característicos del Parkinson.

## Modelo
Para extraer los landmarks, se utilizó Mediapipe, y las máscaras se clasificaron con una red densa de 7 capas.

## Frase
El propósito principal es clasificar los movimientos motores a partir de los puntos clave del rostro.

## Imagen del Proyecto
![Presentacion](presentacion.pdf)



