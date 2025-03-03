<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Las conexiones están direccionadas por una entrada por medio de vcc (voltaje corriente continua), al momento de recibir la señal pasará por las resistencias, la cual entra a una placa que transforma la señal 1 a 0 , pasando por unas compuertas NOT, en ese momento los 0 se vuelven 1, y pasan por otras compuertas llamadas AND, las primeras AND transforman la señal en 0, las segundas en 0 y al final, dependiendo las compuertas, las señales son 0 o 1, al recibir 2 señales a la vez  las compuertas van generando una señal.

Explain how your project works

Tabla de entradas y salidas
![image](https://github.com/user-attachments/assets/34dafd4c-19b1-46ad-ab33-5741bc8f2dc3)

Circuito con todas las salidas en Cero

![Imagen de WhatsApp 2025-03-03 a las 11 43 52_6380e6a2](https://github.com/user-attachments/assets/7c9b1204-5ddc-4513-a473-8bc902cfb6e7) 


LED Rojo se encenderá cuando el número 6 del switch se pone en ON el cual indicará el inicio del proceso.

![image](https://github.com/user-attachments/assets/e44fb032-97bc-4179-b5ba-ab38c8373e64)

LED AZUL-AXILA IZQUIERDA
se encenderá cuando el número 1 del switch se pone en ON el cual indicará una señal de alerta.
![image](https://github.com/user-attachments/assets/c02dad3d-27e4-48ad-9755-940f352f07b8)
LED AZUL CIELO-AXILA DERECHA
se encenderá cuando el número 2 del switch se pone en ON el cual indicará una señal de alerta.
![image](https://github.com/user-attachments/assets/d4a92e2f-c265-406f-90ba-99d5ff68e8cd)

LED AMARILLO INGLE IZQUIERDA
se encenderá cuando el número 3 del switch se pone en ON el cual indicará una señal de alerta.

![Imagen de WhatsApp 2025-03-01 a las 07 51 41_c7512c37](https://github.com/user-attachments/assets/93ac7e1e-e961-4514-8cd6-f28804106f0b)

LED MORADO INGLE DERECHA
se encenderá cuando el número 4 del switch se pone en ON el cual indicará una señal de alerta.
![Imagen de WhatsApp 2025-03-01 a las 07 51 41_adaeba11](https://github.com/user-attachments/assets/f5b89a92-eace-4f22-b3be-e1965a52a510)


## How to test
Para activar el funcionamiento de este circuito, primero es necesario encender el switch número 6, el cual iluminará su respectivo LED rojo, indicando que el sistema está habilitado.

Una vez activado el switch principal, se podrá encender cualquiera de los LEDs independientes, pero con una condición especial: solo uno de ellos podrá estar encendido a la vez.

Es decir, mientras el switch 6 esté activado:

Si se enciende el LED 1, los demás permanecerán apagados.

Si en su lugar se enciende el LED 2, el LED 1 se apagará automáticamente, y así sucesivamente con los demás LEDs. 
EL LED 5 quedará de respaldo por si algun LED principal presente alguna fallo.

Este diseño garantiza un funcionamiento ordenado y controlado, evitando que múltiples LEDs se activen al mismo tiempo, lo que puede ser útil en sistemas de señalización, tableros de control o indicadores de estado.

Este circuito se propone para el área médica oncológica, este procedimiento se aplica a ciertos tipos de cáncer como lo son:
- Cáncer de ovario
- Cáncer de colon
- Cáncer de estómago
- Cáncer apendicular
- Mesotelioma peritoneal
- Pseudomixoma peritoneal
- Carcinomatosis peritoneal
- Timoma
- Sarcomas de células redondas
- Ascitis maligna

La HIPEC (quimioterapia intraperitoneal hipertérmica) es un tratamiento oncológico que se aplica durante una cirugía para destruir células cancerígenas en el abdomen. 

Es por ello que se propone utilizar este circuito de la siguiente manera: 

Quimioterapia
Al encender el LED rojo indicará que la quimioterapia empezará a circular en una máquina de perfusión la cual calienta a una temperatura entre 41°C y 42°C, y de ahí pasará al abdomen del paciente.

Paciente
Se colocarán 4 termómetros distribuidos de la siguiente manera: Axila derecha (LED azul fuerte), axila izquierda (LED azul cielo), ingle derecha (LED amarillo) e ingle izquierda (LED morado). La temperatura normal del ser humano es de 36.5°C (97.7°F) , cuando la temperatura del paciente se eleva a 37,8°C (100°F) o más se considera una alerta para el paciente ya que una temperatura fuera del rango normal y por tiempo prolongado puede provocar daño neurológico, problemas respiratorios, o convulsiones. 

Se propone usar termopar tipo B de platino y rodio que detectan temperaturas de 0 a 100°C (212F), 1 por cada LED, al llegar a la temperatura de 37,8°C (100°F) el termopar mandará un voltaje que indicará que el paciente se encuentra con fiebre, entonces el equipo médico tomará acciones correspondientes.



## External hardware

No
