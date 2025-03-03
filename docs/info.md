<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Las conexiones están direccionadas por una entrada por medio de vcc (voltaje corriente continua), al momento de recibir la señal pasará por las resistencias, la cual entra a placa que transforma las señal 1 a 0 , pasando por unas compuertas NOT, en ese momento los 0 se vuelven 1, y pasan por otras compuertas llamadas AND, las primeras AND transforman la señal en 0, las segundas en 0 y al final, dependiendo las compuertas, las señales son 0 o 1, al recibir 2 señales a la vez  las compuertas van generando una señal.

Explain how your project works

Tabla de entradas y salidas
![image](https://github.com/user-attachments/assets/34dafd4c-19b1-46ad-ab33-5741bc8f2dc3)

Circuito con todas las salidas en Cero




LED Rojo se encenderá cuando el número 6 del switch se pone en ON el cual indicara el inicio del proceso.

![image](https://github.com/user-attachments/assets/e44fb032-97bc-4179-b5ba-ab38c8373e64)

LED AZUL-AXILA IZQUIERDO
LED AZUL se encenderá cuando el número 1 del switch se pone en ON el cual indicara una señal de alerta.
![image](https://github.com/user-attachments/assets/c02dad3d-27e4-48ad-9755-940f352f07b8)




LED AZUL CIELO-AXILA DERECHO
LED AZUL CIELO se encenderá cuando el número 2 del switch se pone en ON el cual indicara una señal de alerta.
![image](https://github.com/user-attachments/assets/d4a92e2f-c265-406f-90ba-99d5ff68e8cd)

LED AMARILLO INGLE IZQUIERDA
LED AMARILLO se encenderá cuando el número 3 del switch se pone en ON el cual indicara una señal de alerta.

![Imagen de WhatsApp 2025-03-01 a las 07 51 41_c7512c37](https://github.com/user-attachments/assets/93ac7e1e-e961-4514-8cd6-f28804106f0b)

LED MORADO iNGLE DERECHA
LED MORADO se encenderá cuando el número 4 del switch se pone en ON el cual indicara una señal de alerta.
![Imagen de WhatsApp 2025-03-01 a las 07 51 41_adaeba11](https://github.com/user-attachments/assets/f5b89a92-eace-4f22-b3be-e1965a52a510)


## How to test

La HIPEC (quimioterapia intraperitoneal hipertérmica) es un tratamiento oncológico que se aplica durante una cirugía para destruir células cancerígenas en el abdomen. 

Es por ello que se propone utilizar este circuito de la siguiente manera: 

Quimioterapia
Al encender el LED rojo indicara que la quimioterapia empezara a circular en una máquina de perfusión la cual calienta la calienta a una temperatura entre 41°C y 42°C, y de ahí pasara al abdomen del paciente.

Paciente
Se colocarán 4 termómetros distribuidos de la siguiente manera: Axila derecha (LED azul fuerte), axila izquierda (LED azul cielo), ingle derecha (LED amarillo) e ingle izquierda (LED morado). La temperatura normal del ser humano es de 36.5°C (97.7°F) paciente, cuando la temperatura del paciente se eleva a 37,8°C (100°F) o más se considera una alerta para el paciente ya que una temperatura fuera del rango normal y por tiempo prolongado puede provocar daño neurológico, problemas respiratorios, o convulsiones. 

Se propone usar termopar tipo B de platino y rodio que detectan temperaturas de 0 a 100°C 212F), 1 por cada LLED, al llegar a la temperatura de 37,8°C (100°F) el termopar mandara un voltaje que indicara que el paciente se encuentra con fiebre, entonces el equipo médico tomara acciones correspondientes.


## External hardware

No
