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

![image](https://user-images.githubusercontent.com/85134094/125658761-63c362b9-44ce-42df-8bea-492b2165cbb0.png)

El signo negativo se debe a que la resistencia R3 esta polarizada, con el positivo hacia la izquierda y el negativo hacia la derecha esto hace que exista una caída de voltaje por lo tanto se lo coloca con signo negativo.

Para V2=0

![image](https://user-images.githubusercontent.com/85134094/125658793-6a4597d3-315b-4ab7-85ef-c351554208a0.png)

![image](https://user-images.githubusercontent.com/85134094/125658810-76a9591c-26b6-446a-a29d-f0d1fbc9700b.png)

Para comprobar el teorema de superposición que nos dice que la intensidad y el voltaje que pasan por un elemento es igual a la suma de todas las intensidades y voltajes respectivamente, que pasan por dicho elemento, con este principio nos queda de la siguiente manera.
Para el voltaje en la resistencia 3 sumamos los voltajes que estén presentes en este elemento, y de la siguiente manera

![image](https://user-images.githubusercontent.com/85134094/125658827-6e2499c4-ab7c-4845-b564-d35a8abc847b.png)

Para la Intensidad en la resistencia 4 tenemos dos intensidades diferentes por lo cual estas se suman:

![image](https://user-images.githubusercontent.com/85134094/125658851-59dcc6e0-696a-4c11-83f5-1efee7a763ff.png)

Como resultado nos queda la siguiente tabla:

![image](https://user-images.githubusercontent.com/85134094/125658880-d9e2630d-96a3-43d5-9658-bbf5d2284f0d.png)

**5.VIDEO**

https://youtu.be/iI_Y35dYYG4

**5. CONCLUSIONES**

En conclusión, podemos observar que al implementar el teorema de superposición nos permite simplificar circuitos complejos y obtener las incógnitas que se nos presenta de una manera mas ordenada y sencilla que otros métodos de resolución estudiados hasta el momento; siempre y cuando tomemos de manera correcta el sentido en el que circula la corriente.

Como pudimos observar al hacerle un corto en la fuente de voltaje 2 obtenemos una resistencia igual a cero, por lo cual tenemos que tener cuidado al resolver circuitos de este tipo ya que podriamos tener problemas al tratar de sacar las resistencias equivalentes

**6.BIBLIOGRAFÍA**

allan h. robins,  wilhelm c. mille. (2013). Analisis De Circuitos (Vol. 1).

Edimenister, J. A. (Profesor E. de ingiería E. de la universidad de A. (1999). Circuitos eléctricos_3a  edición
