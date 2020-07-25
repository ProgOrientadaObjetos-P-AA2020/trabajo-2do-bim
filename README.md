# Trabajo Final del 2do Bimestre

### Aplicación conceptos de herencia y polimorfismo

**Problemática**

* Se requiere generar una solución que permite administrar el valor de pasaje del transporte intercantonal de la ciudad de Loja.
El pasaje intercantonal tiene la siguientes: nombre-pasajero (tipo **Persona**), cedula, origen,  destino, número km de distancia, tarifa base, valor pasaje.

* Se debe tomar en consideración que existen diversos tipo de transporte:
	- Pasaje Transporte Normal
  		- atributo: porcentaje adicional
  		- El valor del pasaje es igual a (número de km * 0.25) + (tarifa base + (tarifa base*(porcentaje/100)))
	- Pasaje Transporte Menor de Edad
  		- atributo: porcentaje descuento
  		- El valor del pasaje es igual a (número de km * 0.25) + (tarifa base - (tarifa base*(porcentaje/100)))
	- Pasaje Transporte Tercer Edad
  		- El valor del pasaje es igual a (número de km * 0.15) + (tarifa base/2))
	- Pasaje Transporte Universitario
  		- El valor del pasaje es igual a (número de km * 0.10) + (tarifa base/2))


**Tareas**

En una clase Principal usted debe:

* **Generar** un método main que permita ingresar múltiples tipos de objetos de pasajes de transporte con la información por teclado (hasta que el usuario decida); guardar en un estructura ArrayList.
* Se debe **calcular el valor** del pasaje de acuerdo a su contexto.
* **Guardar** la información de cada objeto en un archivo serializado.
* **Obtener** la información del archivo serializado y presentar la información de cada objeto haciendo uso del método toString()

**Recomendaciones**

- Tomar como base el proyecto en Netbeans del repositorio.
- Analizar la problemática, ***leer cada clase del proyectos Netbeans*** y construir su solución.

**Salida Tipo**

***

	Lista de Pasajes
	
	1) PasajeNormal
	200,00
	
	2) PasajeMenorEdad
	100,00
	
	3) PasajeTerceraEdad
	300,00
	
	4) PasajeUniversitario
	400,00
	
	5) PasajeNormal
	200,00
	
	6) PasajeMenorEdad
	100,00


***

**Atención**

En cada objeto de la ***salida tipo*** solo se presenta el posible valor del pasaje, usted debe presentar todas las características posibles de cada tipo de objeto.

**Fecha de presentación**

Miércoles 29 de julio de 2020
