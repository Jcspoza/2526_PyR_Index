# Indice - Taller PyR 2025 - 2026 en CMM Benito Martin Lozano

## Adaptación del Programa del curso 25 - 26 a los alumnos

El programa se adaptará a los alumnos como se hizo los dos cursos anteriores. Si hay alumnos nuevos con un nivel bajo, lo que haremos será aplicar alguna o todas de estas estrategias

- Robotica : dispositivos de entrada que no se ha dado de forma completa

- Programación: reforzar conceptos repasando "Invent with Python " y otros libros / guías

- Dividir el tiempo de clase en 1ra parte nivel bajo -> 2da parte nivel medio

## Indice de clases (a adaptar)

Se irán publicando los enlaces a las clases aqui

| Link y Titulo                                                                                   | Contenido                                                                                                                                                                                                   | Impartida |
| ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| [CL0 - Presentación Taller PyR + Demos](https://github.com/Jcspoza/2526CL0_PyR_Intro/tree/main) | Requisitos de entrada / Presentaciones / Que es la robotica / Enfoque del taller/ Que herramientas vamos a necesitar/ Funcionamiento de las clases / 2 demos:                                               |           |
| [CL1 - Circuitos electrónicos 0](https://github.com/Jcspoza/2526CL1_R_CircElect0)               | Modelo simple de electricidad / uso de la protoboard / Circuitos simples desde 0 :  bombillas, leds, resistencias, ley ohm -> interruptor mecánico, interruptor 'reed',  interruptor magnético con IC A3144 |           |
| CL2- Primer programa en Python                                                                  | CL1 PTSD 3y4ESO: on line python / si da tiempo ver colab                                                                                                                                                    |           |
| CL3- Adivina Numero en Python                                                                   | CL2 PTSD 3y4ESO : online python                                                                                                                                                                             |           |

--------

## <u>Referencias varias</u>

### Libros y webs de referencia para TODO EL CURSO

#### Libros Python

* [Invent with Python](https://inventwithpython.com/invent4thed/) en ingles , web gratuita con el libro completo + programas en python

    Se puede descargar una [versión en Castellano en pdf aqui](./doc/Inventa_Juegos_con_Python_4ed.pdf)

* [web de referencia de Python en castellano](https://ellibrodepython.com/)

#### IDE´s of y on line

On-line : el IDE mas básico para Python : [Online Python](https://www.online-python.com/)

On-line + cuaderno tipo Jupiter : [Google Colab](https://colab.research.google.com/#scrollTo=Wf5KrEb6vrkR)

#### Libros y tutoriales de Electrónica básica

- [Electronica para makers - Paoplo Aliverti - Ed marcombo](./doc/edoc.site_electronica-para-makers-paolo-aliverti.pdf)

- 

#### Tutoriales Pico W en micropython

* [Oficial-Introduction to Raspberry Pi Pico guide](https://projects.raspberrypi.org/en/projects/introduction-to-the-pico/0)

* [Oficial- Getting started with your Raspberry Pi Pico W](https://projects.raspberrypi.org/en/projects/get-started-pico-w/0)

* [Buena web de tutoriales -Sunfounder](https://docs.sunfounder.com/projects/kepler-kit/en/latest/pyproject/for_micropython_user.html)

* [Otra buena web de tutoriales - Freenove ¡El tutorial incluye el nuevo Pico 2!](https://github.com/Freenove/Freenove_Super_Starter_Kit_for_Raspberry_Pi_Pico/tree/main/Python)

### Tabla resumen de programas básicos de test

| Programa                          | Lenguaje                    | Objetivo del programa                                                   | Notas                                                        |
| --------------------------------- | --------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------ |
| Rbhwt_BlinkLedInt                 | micropython (uPython, o uP) | Probar la tarjeta del micro controlador : Pico, PicoW, Pico 2 y Pico 2W | Pico y PicoW tienen el led interno con direcciones distintas |
| [Hola mundo](./P_2425CL0_hola.py) | Python                      | Primer programa de Python                                               | Input() no funciona con algunos IDE python en web (on line)  |

## Enfoque: ¿Por qué Programación y Robotica simultáneamente?

La frontera es difusa, hay diferencias al comienzo del aprendizaje de Programación o
Robotica, que luego cuando se avanza se reducen. Lo ideal sería aprender tanto
Programación como Robótica.

| PROGRAMACION                                                                                                                                                  | ROBÓTICA                                                                                                            |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Mas Abstracto, los programas se ejecutan en un ordenador y no interactúan con el mundo salvo el teclado y la pantalla (hasta que se hacen cosas con internet) | Mos concreto, se pueden hacer "cacharros" como termostatos, estaciones meteorológicas, etc                          |
| Rápidamente se avanza a programas más complejos y más “inteligentes”                                                                                          | Los programas que se cargan en el microcontrolador son relativamente simples, aunque poco a poco se van complicando |
| No se necesita hardware para empezar (microcontrolador y materiales de robótica), salvo un PC o similar                                                       | Se NECESITA hardware para empezar: materiales de robótica y microcontrolador                                        |

En <u>programación</u>, **Python** es sin duda el lenguaje mas adecuado para aprender (en edad adulta) porque es :

- **Gratis** (al igual que su código fuente y sus bibliotecas).

- **Fácil de aprender y de usar**. Beneficia tanto a los principiantes como a los expertos.

- **Sintaxis legible**.

- **Libre** y de **código abierto** (open source).

- Amplias **bibliotecas**.

- **Creación rápida** de programas: ***es un lenguaje Interpretado***

- **Extensible e integrable** con otros lenguajes

- Funciona en los principales sistemas operativos y plataformas informáticas

Mas razones en los siguientes videos

[Video corto en castellano 1 ](https://www.tiktok.com/@edteam/video/7410916311821323526?is_from_webapp=1&web_id=7343715684931307040)

[Video corto en castellano 2](https://www.tiktok.com/@edteam/video/7410916311821323526?is_from_webapp=1&web_id=7343715684931307040)

[3 Reasons to Learn Python - AI and LLMs is One of Them, but There are MORE!](https://www.youtube.com/watch?v=EHsLuHbE_9s)

En <u>Robotica</u>, hasta hace poco tiempo había que usar para programar los microcontroladores , que son el cerebro de los proyectos de robotica, lenguajes relativamente oscuros como "C" o derivadas de C ( IDE Arduino) . Afortunadamente, en 2013 el físico Australiano Damien George, desarrollo junto a otros personas **micropython** para el microcontrolador PyBoard, y rápidamente se "porto" a otros microcontroladores como ESP32 o RPI Pico.

**Micropython** es una implementación del lenguaje de programación Python 3, escrita en C, optimizada para poder ejecutarse en un microcontrolador. Es decir **permite programar los microcontroladores con "programas" escritos en un sub-conjunto de Python con alguna peculiaridad del microcontrolador** por lo que son aplicables todas las ventajas de Python

***En este curso se aprende simultáneamente Python y microPython con lo cual el aprendizaje se realimenta y multiplica***

---
