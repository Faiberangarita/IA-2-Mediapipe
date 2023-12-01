# IA-2-Mediapipe
## Proyecto de IA-2 para la prediccion de puntos clave del rostro con openpose
El Dataset esta construido por dos clases de pacientes: Control(7 pacientes) y Parkinson(7 pacientes) para un total de 14 pacientes.


Cada Paciente en el dataset dice las siguietnes palabras


-3 veces las vocales(A,E,I,O,U)


-9 veces una palabra separandola por silabas, ejemplo: PE-TA-KA.


-54 palabras, ejemplo Agarrar, Hospital.


De esta forma cada paciente es grabado en video diciendo multiples palabras, para un total de 924 videos.

## Descripcion del proyecto


El objetivo de nuestro proyecto es hallar los puntos clave del rostro para cada paciente y clasificarlo como Parkinson o Control, Teniendo encuenta que esta es la primera fase de una tesis de grado se busca para este proyecto replicar y mejorar la arquitectura de Openpose con los metodos vistos en clase.


## Frase
Clasificar los moviminetos motores apartir de puntos clave del rostro

## Arquitectura de Openpose
![sacado del journal https://arxiv.org/pdf/1812.08008.pdf ](arquitectura.png)

## Resultado esperado para cada paciente
![Deteccion de 70 puntos clave ](rostro.gif)

## Autores del proyecto
Faiber Stiven Angarita Mendoza

