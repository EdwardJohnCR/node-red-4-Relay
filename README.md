# Node Red 4 relay

Hola!, saludos a todos, les comparto un proyecto en Node Red corriendo en Raspberry 3 o 4, es una sección de un proyecto en producción trabajando 24/7, 30 meses en 20 sitios distintos.
El problema que presenta es en la SD de la Raspberry, si ocurre un cambio brusco al voltaje se quema la SD.
Si la Raspberry requiere trabajo full time, protector de picos es la solución al cambio de voltaje.
---

# Vamos al Proyecto
---
## Accesos y control de Luz

Dashboard control 3 relay, dos portones impulsos secos (tipo timbre), un switch control de la luz.
LED indicadores.
Estado de la luz suscrito a un tópico en el servidor MQTT.
Reloj.

![](https://foro.crcibernetica.com/uploads/default/optimized/1X/81612ca44f0eb7d00b4f7fcefb1e5c3ba05797ce_2_690x363.png)

## Control de Activación de Sirena

Switch de seguridad para confirmar la activación de la sirena de pánico, evitando una activación por error.
LED indicadores.
Dos botones uno de 5 segundos de activación y otro de 30 segundos.
Reloj.

![](https://foro.crcibernetica.com/uploads/default/optimized/1X/6115c6474bdda3ab8bde1372a1af94934e8040d1_2_690x335.png)

## Monitoreo de RED

Monitoreo de ping a distintos servicios dentro o fuera de la red.

![](https://foro.crcibernetica.com/uploads/default/optimized/1X/6e17e6b172ee0ad851812be3b2697525ad355214_2_690x270.png)

El flow se puede descargar de GitHub en el siguiente enlace:
https://github.com/EdwardJohnCR/node-red-4-Relay/archive/refs/heads/main.zip

## Módulos

Al importar el proyecto a Node Red, se requiere la instalación de los siguientes módulos para un correcto funcionamiento:

![](https://foro.crcibernetica.com/uploads/default/optimized/1X/bc61dad4438e1d913503f0e302fd193255be8769_2_418x500.png)

## Flow

Al completar la instalación de los módulos, uno de los flow se vería de la siguiente manera:

![](https://foro.crcibernetica.com/uploads/default/optimized/1X/e795d9eb9b1f47348e1e01d0fd0ed1439f8d7cc8_2_690x447.png)

## APP

Se puede integrar con cualquier aplicacion MQTT Dasboard (ejemplo MQTT DASH)

![](https://foro.crcibernetica.com/uploads/default/optimized/1X/0b69ecda13be380d56cc32897fa606aa1c0ef002_2_236x500.jpeg)

Espero les aporte esté proyecto, saludos…





