# Guía de uso CNC Othermill Exploratec
Instructivo de la utilización de la maquina Othermill de Bantam Tools para su uso en el taller de Exploratec UDD.

![foto maquina](img/maquina.JPG)

------------------------

$$\color{red}\Huge{\textsf{Considerar!}}$$

## Precauciones

- Verificar que no haya gente transitando mientras se vaya a usar
- Verificar sujeción de la fresa 
- MAntenerse junta a la maquina mientras está trabajando

## Herramientas

###### Fresas para el mecanizado:
- Fresa de grabado punta V 
- Fresa en espiral
(más adelante se especifica)

###### Para el cambio y sujeción de fresa:
- Llave punta corona 13mm
- Llave punta corona 17mm

------------------------

## Uso
La cnc othermill es una fresadora por control numérico computarizado, y al igual que una impresora 3d o una cortadora láser nos ayuda con la manufactura de productos, en este caso específicamente en la producción de circuitos en placas PCB.

>![Discrete diode-transistor logic printed circuit modules manufactured in the German Democratic Republic. Produced in the 1960s](img/pcbEjemplo.jpg)
<a href="https://commons.wikimedia.org/wiki/File:GS48_63.jpg">Mister rf</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>, via Wikimedia Commons

### PCB
>*En electrónica, una placa de circuito impreso es una superficie constituida por caminos, pistas o lapices de circuitos buses de material conductor laminadas sobre una base no conductora. El circuito impreso se utiliza para conectar eléctricamente a través de las pistas conductoras, y sostener mecánicamente, por medio de la base, un conjunto de componentes electrónicos. Las pistas son generalmente de cobre, mientras que la base se fabrica generalmente de resinas de fibra de vidrio reforzada, cerámica, plástico, teflón o polímeros como la baquelita.*
>[Wikipedia](https://es.wikipedia.org/wiki/Circuito_impreso)

Las PCB o **placas de circuito impreso**, son usadas para la **producción serializada** de componentes electrónicos, y su uso se extiende a la mayoría de productos con alguna clase de circuito. Al desarrollar un proyecto que cuenta con algún circuito se suele comenzar prototipando en un *protoboard*, dicho prototipo tendría como objetivo validar el funcionamiento de la electrónica, tras ello el siguente paso sería fabricar el circuito en PCB, esta vez pensando en dimensiones físicas, ensambles, y en la integralidad del producto.

>![Canon PowerShot G11 - Rear view of the interior.jpg](img/interiorCamara.jpg)
<a href="https://commons.wikimedia.org/wiki/File:Canon_PowerShot_G11_-_Rear_view_of_the_interior.jpg">Teardown Central</a>, <a href="https://creativecommons.org/licenses/by-sa/2.0">CC BY-SA 2.0</a>, via Wikimedia Commons

Una placa PCB cuenta con varias capas, pero en su forma básica tiene una capa de sustrato y una capa de cobre, existen algunas con más capas de estas, e incluso con otras capas.

La capa de sustrato está hecha de un material aislante, y la capa de cobre, debido a su composición, es conductiva. Esto permite generar conexiones eléctricas entre distintos componentes sustrayendo cobre de la placa, generando las llamadas pistas.

>![capas de una pcb](img/pcbCapas.png)
<a href="https://commons.wikimedia.org/wiki/File:Layers_of_Single-Layer_PCB_Simplified.svg">Gregortiverse</a>, CC0, via Wikimedia Commons

Para el diseño de estas placas existen softwares en los que se pueden generar esquemáticos y placas, como KiCad, Fritzing, o Autodesk Eagle; de las tres se recomienda **KiCad** por ser open source y por contar con mantenimiento regular.

TODO foto kicad

## La máquina
El modelo de la CNC es **Othermill Pro** de *Other Machine Co.* 
|**Othermill Pro**
:----:
![foto](img/maquina.JPG)

|Botón de emergencia | Portaherramienta
---------------------|-------------------------
![foto](img/champi.JPG) | ![foto](img/fresaPuesta.JPG)

|Cama del CNC
:----:
![foto](img/cama.JPG)

En la parte trasera de la máquina está el interruptor de encendido, la conexión a la corriente y al computador.

|Parte trasera|
:------:
![foto maquina conectada](img/maquinaConectada.JPG)

|Encendido y alimentación | Puerto USB tipo B 
---------------------------|-------------------------------
![foto maquina fuente](img/maquinaFuente.JPG) | ![foto maquina u s b](img/maquinaUSB.JPG)

TODO hablar de las acciones al usarla, desde el encendido

### Las fresas
TODO Fresas para las pistas

TODO Fresas para corte

## El software
TODO hablar de la versión compatible y donde encontrarla

TODO funciones del software

>#### El siguente paso
>Si ya lograste producir tus circuitos PCB con la Othermill te invitamos a dar el siguiente paso investigando más sobre la manufactura de circuitos, hay muchos tipos y técnicas, como también tienes la posibilidad de delegar la manufactura en un tercero como JLC-PCB y PCB-Way.

>documentado por [AndresMartinM](https://github.com/AndresMartinM) y por [ElPerroGCP](https://github.com/ElPerroGCP) 2025