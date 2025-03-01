<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Las conexiones están direccionadas por una entrada por medio de vcc (voltaje corriente continua), al momento que las corrientes pasan por unas resistencias, de ahí, van  a una placa input que transforma las señal 1 a 0 , pasando por unas compuertas NOT, en ese momento los 0 se vuelven 1, y pasan por otras compuertas llamadas AND, las primeras AND transforman la señal en 0, las segundas en 0 y al final, dependiendo las compuertas, las señales son 0 o 1, al recibir 2 señales a la vez  las compuertas van generando una señal

Explain how your project works

TABLA BINARIA
![image](https://github.com/user-attachments/assets/34dafd4c-19b1-46ad-ab33-5741bc8f2dc3)

CIRCUITO DE COMPUERTAS
![image](https://github.com/user-attachments/assets/e44fb032-97bc-4179-b5ba-ab38c8373e64)

EN LA IMAGEN COMO SE PUEDE OBSERVAR NO ESTA DANDO NINGUN TIPO DE SEÑAL A ALGUN LED LO CUAL NOS ESTA INDICANDO QUE LA TEMPERATURA DEL PACIENTE ES ESTABLE POR EL MOMENTO

LED AZUL-BRAZO IZQUIERDO
![image](https://github.com/user-attachments/assets/c02dad3d-27e4-48ad-9755-940f352f07b8)

EN EL DIAGRAMA YA ESTA HACIENDO SU PRIMERA SEÑAL, LA CUAL SU FUNCION SERIA SER UN TESTIGO(LED AZUL) LA CUAL ESTARIA INDICANDO QUE LA TEMPERATURA LLEGO A SU MAXIMO Y DEBE DISMINUIR PARA NO LLEGAR A CAUSAR ALGUN TIPO DE ERROR Y NO SE CONCLUYA LA QUIMIOTERAPIA

LED AZUL CIELO-BRAZO DERECHO
![image](https://github.com/user-attachments/assets/d4a92e2f-c265-406f-90ba-99d5ff68e8cd)

NUEVAMENTE EN EL DIAGRAMA ESTARIA DANDO UNA SEÑAL UN LED, LA CUAL ESTA INDICANDO QUE LA TEMPERATURA DEL CUERPO DEL PACIENTE A LLEGADO A SU LIMITE Y DEBE DISMINUIR, LO CUAL HARIA UN "STOP" EN LA QUIMIOTERAPIA(ACLARAMOS QUE CUALQUIER LED QUE SE LLEGUE A ENCENDER LA QUIMIOTERAPIA SE DETENDRIA)


CON LOS ANTERIORES DOS EJEMPLOS SE MUESTRA LA FUNCION DE LO QUE HARIAN LOS LEDS JUNTO CON UNOS TERMOMETROS, LLEGANDO A MANDARNOS SEÑALES QUE LA TEMPERATURA DEL CUERPO DEL PACIENTE LLEGO A SU LIMITE Y DEBE BAJAR SU TEMPERATURA PARA CONTINUAR SU TRATAMIENTO CON MAYOR EFECTIVIDAD, EL UNICO PROBLEMA QUE PRESENTA EN EL MOMENTO QUE LLEGUE A HABER DOS TESTIGOS NINGUNO DE ELLOS PRENDERIA, PERO HARIA LA FUNCION DE PARAR LA QUIMIOTERAPIA DE TODAS FORMAS, MO TENDRIAMOS ALGUN TIPO DE PANTALLA LDC O OLED PARA QUE NOS MUESTRE LA TEMPERATURA QUE ESTA EL PACIENTE, PERO AL MOMENTO QUE LA TEMPERATURA DISMINULLA LOS TESTIGOS DESAPARECERIAN Y NUEVAMENTE SE PONDRIA EN FUNCION LA QUIMIOTERAPIA, ASI CONSECUTIVAMENTE ASTA QUE SE FINALICE EL TRATAMIENTO O EL DOCTOR DE DE ALTA EL TRATAMIENTO





## How to test

Explain how to use your project

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
