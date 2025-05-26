# Guía de uso CNC Othermill Exploratec
Instructivo de la utilización de la maquina Othermill con Bantam Tools para su uso en el taller de Exploratec UDD.

----

$$\color{red}\Huge{\textsf{Considerar!}}$$

### Mañas del proceso

Algunas de las funcionalidades del software de Bantam Tools tienen problemas si no se realizan de una menera en específico:

- Al digitar números decimales usar la coma en lugar de puntos (ej:0,2), esto se debe corregir cada vez que se cambia un número.
- Al realizar un cambio en un valor, u opción, se debe presionar Intro para configurar la modificación.

Además se deben tomar todas las precauciones indicadas anteriormente:

### Precauciones

- Verificar que no haya gente transitando mientras se vaya a usar
- Verificar sujeción de la fresa 
- Mantenerse junto a la maquina mientras está trabajando
- Mantener las tapas acrílicas cerradas

Así como también contar con las herramientas necesarias:
### Herramientas

###### Fresas para el mecanizado:
- Fresa de grabado punta V 
- Fresa en espiral
(más adelante se especifica)

###### Para el cambio y sujeción de fresa:
- Llave punta corona 13mm
- Llave punta corona 17mm

###### Para el mantenimiento:
- Retirar la fresa por precaución
- Usar la aspiradora para retirar el polvo

----

## Paso a paso

Teniendo la máquina encendida y conectada vía USB, y el computador con el programa de Bantam Tools abierto podrás comenzar con lo siguiente: 

### Movimiento del cabezal

Antes de comenzar se debe conocer el manejo del movimiento de la fresa, para esto hay que abrir el menu **JOG** que se encuentra en la esquina inferior izquierda. En él se podrá mover presionando las flechas que dicen `-X` `+X` para los lados, `-Y` `+Y` para adelante y atras, y `-Z` `+Z` para arriba y abajo. Además están los botones: `HOME` para volver al origen, y `ORIGIN` para guardar un nuevo origen en las coordenadas actuales, el último es `INSTALL TOOL` que nos sirve para que la máquina reconozca la altura de la fresa que esté instalada.

### Fabricación de una PCB

Para la fabricación de una placa hay que tener una PCB sin perforar de una o dos capas (se recomenda trabajar con una sola capa para evitar problemas de calces), y esta habrá que dimensionarla y adherirla a la cama de la othermill. Para el dimensionado en el taller contamos con dremell y su disco de corte, y para pegarla a la cama de aluminio usamos cinta doblefaz delgada (no de la acolchada) y la pegamos calzando en una de las esquinas delanteras.

En la pestaña `Material Setup` podremos configurar el tamaño de nuestra placa (Figura A.6), en el caso de las PCB que usamos el espesor es 1.6mm por lo que en eje z ponemos 1,6, el X e Y dependerán de como lo hayamos dimensionado. Dependiendo de en qué esquina hayamos adherido la placa seleccionamos 

| A. ***Material Setup*** |
|:---:|
| A.1 Instalar fresa |
![](img/paso2.png)
| A.2 Seleccionar fresa |
![](img/paso1.png)
| A.3 Elegir fresa a instalar |
![](img/paso3.png)
| A.4 Confirmar fresa para iniciar instalación |
![](img/paso4.png)
| A.5 Posicionar fresa **sobre aluminio** |
![](img/paso5.png)
| A.6 Configurar tamaño del material |
![](img/paso6.png)
| A.7 Definir offset y posición del material |
![](img/paso7.png)

TODO emilioooo escribir las instruciones de configuración de archivo

| B. ***File Setup*** |
:---:
| B.1 Seleccionar archivo |
![](img/paso8.png)
| B.2 Configurar fresa y parámetros |
![](img/paso9.png)
| B.3 Generar GCODE (revisar previo al fresado) |
![](img/paso10.png)

| C. ***Plan Setup*** |
:---:
| C.1 Configurar offset |
![](img/paso11.png)
| C.2 Revisar selección de fresa y comenzar fresado |
![](img/paso12.png)



---

##### El siguente paso
###### Si ya lograste producir tus circuitos PCB con la Othermill te invitamos a dar el siguiente paso investigando más sobre la manufactura de circuitos, hay muchos tipos y técnicas, como también tienes la posibilidad de delegar la manufactura en un tercero como JLC-PCB y PCB-Way.

>documentado por [AndresMartinM](https://github.com/AndresMartinM) y por [eeminionn](https://github.com/eeminionn) 2025