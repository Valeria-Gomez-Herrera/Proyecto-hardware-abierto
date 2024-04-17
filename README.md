# Proyecto-hardware-abierto
## Integrantes
* Noah Noel Arredondo Torres
* Valeria Gómez Herrera
* Juan David Lara Robles

## Software Utilizado
|Nombre del Software|Tipo|
|-------------------|----|
|Platformio IDE|	Software Libre (Herramienta Desarrollo C) |
|Flutter|Framework de código abierto |
|Firebase|Plataforma en la nube|

## Comunicación
* La comunicación que existe entre el circuito, la base de datos y la aplicación funcionan de la siguente manera: <br>
Primero tenemos nuestra interfaz la cual el usuario tiene que logearse para despues poder visualizar la temperatura, humedad y el tiempo.<br>
* Despues tenemos nuestro circuito el cual mide la temperatura y humedad dependiendo de el lugar en el que nos encontremos, los resultados de estos los guarda en la base de datos y a su vez los muestra en la pantalla de nuestra aplicación.
* Nuestra base de datos almacena los datos del sensor de humedad y temperatura, para despues mostrarlos en la aplicación. Los datos cambian cada ves que el sensor arroja nuevos resultados.

## Base de Datos
Esta es la estructura de la base de datos que fue hecha en Firebase

**devices {** <br>
	**temperature: (String),** <br>
	**humidity: (String),**<br>
	**timestamp: (Date)**<br>
**}**<br>

## Circuito

