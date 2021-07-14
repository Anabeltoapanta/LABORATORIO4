# LABORATORIO4

AUTORES: MEJIA CESAR-MONTALVO STEVE - TOAPANTA ANABEM

**1 . OBJETIVOS**

Objetivo General

Comprobar el teorema de superposiciones de forma experimental mediante la resolución de un circuito y su respectiva simulación.

Objetivos Especificos

* Resolver un circuito electico mediante el teorema de superposiciones
* Mostrar un circuito de forma experimental por medio de un simulador virtual.
* Considerar correctamente la polaridad del voltaje y  el sentido corriente de nuestro circuito.
* Comprobar los resultados obtenidos teóricamente mediante la simulación respectiva del circuito .




**2.MARCO TEORICO**

Teorema de superposición:
Es un método que permite determinar la corriente o voltaje en cualquier resistor en una red, una de las ventajas de este método es que no requiere usar matrices o determinantes para estudiar el circuito, el teorema determina que: “La corriente total o el voltaje en un resistor o una rama puede determinarse mediante la suma de los efectos debidos a cada fuente independiente.” (allan h. robins, 2013); Para utilizar este teorema es necesario eliminar todas las fuentes de voltaje, a excepción de la que se esta analizando, se dice que para poner en cero las fuentes de voltaje se debe remplazar por un cortocircuito.
Una fuente de corriente se hace cero al remplazarla con un circuito abierto, a través del cual la corriente es cero amperios, para lo cual se determina que la potencia disipada por cualquier resistor, primero se debe encontrar el voltaje o la corriente del resistor.

![](https://github.com/Anabeltoapanta/LABORATORIO4/blob/main/FORMULA.png)
                                                                                                   
La superposición solo puede utilizarse cuando las funciones de control son externas al circuito
(Edimenister, 1999)

![](https://github.com/Anabeltoapanta/LABORATORIO4/blob/main/Teorema%20de%20superposici%C3%B3n_page-0001.jpg)
                                             

**3.EXPLICACIÓN DEL PROCEDIMIENTO**

Según lo planteado anteriormente el análisis de del circuito aplicando el Teorema 
de Superposición nos va a simplificar los cálculos de circuitos mixtos en donde 
involucren más de dos fuentes de voltaje o intensidad en este caso tenemos dos 
fuentes de voltaje que las analizaremos por separado.
Para ello vamos a necesitar materiales y herramientas que son las siguientes

Material y equipo requerido

- 2 Fuentes de voltaje de C.D

- 2 Multímetros digitales

- 1 resistor de 1kiloohm

- 1 resistor de 2.2 kilo ohmios

- 1 resistor de 820 ohmios

- 1 resistor de 470 ohmios

- 1 Protoboard

**Procedimiento**

Para nuestra practica necesitamos saber previamente dicho teorema que nos dice que 
el voltaje o corriente a través de cualquier elemento del circuito puede obtenerse 
sumando algebraicamente todos los voltajes o corrientes generados por cada fuente 
actuando por si sola, con todas las demás fuentes igualadas a cero. Este concepto 
dependerá si tenemos fuentes de voltaje o fuentes de intensidad.

En este caso como tenemos fuentes de voltaje estas igualadas a cero equivalen a un 
corto circuito. 

Como primer parámetro necesitamos realizar un diagrama esquemático como lo vemos a 
continuación

Para ello los pasos que seguiremos son los siguientes:

1)	Procederemos a simular el circuito en Tinkercad de la siguiente manera 

 ![image](https://user-images.githubusercontent.com/85134094/125635653-fe698c7f-a548-48a9-9335-bd082ade6f25.png)

2)	Vamos a empezar igualando la fuente de voltaje de 20 Voltios a cero, esto 
quiere decir que estará en cortocircuito como se muestra a continuación.

![image](https://user-images.githubusercontent.com/85134094/125635710-e16215d9-0328-4b70-b0e8-2760a04a3e23.png)

3)	A continuación, procedemos con la medición del voltaje de la resistencia de 
820ohm y la intensidad que pasa por la resistencia de 470 ohm

![image](https://user-images.githubusercontent.com/85134094/125635805-b95a39ec-b584-47d1-92a4-24e9705d01ab.png)

Como podemos observar nos va a marcas un voltaje y una intensidad con referencia a la única fuente de voltaje conectada

4)	A continuación, procedemos a igualar la fuente de voltaje de 12 Voltios a cero, esto quiere decir que estará en cortocircuito como se muestra a continuación 

![image](https://user-images.githubusercontent.com/85134094/125635885-f012a18d-983a-4cce-85b9-f994dd8f051b.png)

5)	A continuación, procedemos con la medición del voltaje de la resistencia de 820ohm y la intensidad que pasa por la resistencia de 470 ohm

![image](https://user-images.githubusercontent.com/85134094/125635915-95b535b0-9c5f-41df-9925-20d12c64bc51.png)

Como podemos observar nos va a marcas un voltaje y una intensidad con referencia a la única fuente de voltaje conectada

6)	Y Finalmente procedemos con la medición del voltaje de la resistencia de 
820ohm y la intensidad que pasa por la resistencia de 470 ohm con ambas fuentes de 
voltaje conectadas

![image](https://user-images.githubusercontent.com/85134094/125635989-585bd532-6f8d-4454-a4d8-e2c5a4cc3111.png)

**4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

A continuación, procederemos a realizar los cálculos para demostrar que los datos medidos anteriormente en la practica sean los correctos. 

Para ello nos ayudaremos de la ley de ohm para realizar los cálculos de las resistencia, intensidad y voltaje total como se muestra a continuación

Para V1=0

![image](https://user-images.githubusercontent.com/85134094/125636064-12d2de18-d36b-4e10-816b-fedadf8e9d5f.png)

![image](https://user-images.githubusercontent.com/85134094/125636092-2a6f40b4-2038-4e11-80cb-07b1c154134f.png)

![image](https://user-images.githubusercontent.com/85134094/125642424-5d168b8e-a9eb-432c-8203-85f2220d10c3.png)

Para V2=0

![image](https://user-images.githubusercontent.com/85134094/125636146-ef2cc837-aaae-4c91-8441-2e3e9371ffcf.png)

![image](https://user-images.githubusercontent.com/85134094/125636177-bd88745b-1b29-4e4f-b6bf-decbe69d38b9.png)

![image](https://user-images.githubusercontent.com/85134094/125636196-49d5c2da-26c0-44ee-93b8-c5d8ebcc341b.png)

Para cumplir con el teorema de superposición se debe sumar dichos voltajes 

Para el V3

![image](https://user-images.githubusercontent.com/85134094/125636427-41629b41-03d4-402a-b8c5-1bb545a0b38d.png)

Para la I4 
Para el calculo de la intensidad 4 se toma solamente el voltaje de la segunda fuente por lo que esta conectado directamente a la resistencia 4 por lo que nos queda como resultado 

![image](https://user-images.githubusercontent.com/85134094/125636463-3c3ca1fe-43c6-4381-a259-01044c369806.png)

Como resultado nos queda las siguientes tablas:

![image](https://user-images.githubusercontent.com/85134094/125636533-811b8ec3-fc9e-47f1-bb6d-2da90e83376c.png)


**5.VIDEO**

https://youtu.be/E5_X9gLqero

**5. CONCLUSIONES**



**6.BIBLIOGRAFÍA**

allan h. robins,  wilhelm c. mille. (2013). Analisis De Circuitos (Vol. 1).

Edimenister, J. A. (Profesor E. de ingiería E. de la universidad de A. (1999). Circuitos eléctricos_3a  edición
