# LABORATORIO # 05

TEMA: TEOREMA DE THÉVENIN
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Analizar experimentalmente el Teorema de Thévenin en un circuito resistivo.

**1,2.-ESPECÍFICOS**

* Comprobar un circuito de corriente directa mediante la aplicación del Teorema de Thevenin .

* Verificar la manera de medir la resistencia y voltaje Thevenin de un circuito.

* Reducir y solucionar un circuito mediante el Teorema de Thévenin.


## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito mixto lineal, en un programa online denominado Tinkercad con la finalidad de experimentarel análisis mediante el Teorema de Thévenin. Se crea el circuito utilizando resistencias en serie y paralelo conectadas a fuentes variables, la cuál es la característica principal para poder utilizar el Teorema de superposición como un método de solución factible.


## 3. MARCO TEÓRICO 

**TEOREMA DE THÉVENIN**

El teorema de Thévenin determina que un circuito eléctrico con dos fuentes de alimentación es equivalente a un circuito formado por una fuente de tensión Vth (Voltaje de Thévenin) en serie con una resistencia Rth (Resistencia de Thévenin).
  
![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/Thevenin.png)

Para aplicar este método primero tenemos que tomar en cuenta que:
* Las fuentes de voltaje se cierran.
* Las fuentes de corriente se abren.
* La resistencia a la cual vamos a calcular su voltaje y corriente, se abre.

Para aplicar el teorema correctamente, se deben realizar estos pasos:

1.	Al eliminar las fuentes de tensión o fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thévenin. Se procede a calcular el valor de la resistencia total existente entre los punto A y B donde se encuentre conectada la resistencia de carga.

2.	Para el caso de hallar la tensión de Thévenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde ésta se encontraba.

3.	Construimos el circuito equivalente utilizando la tensión de Thévenin y la resistencia de Thévenin en serie y procedemos a conectar la resistencia de carga entre los puntos de conexión abiertos.

4.	Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

## 4. DIAGRAMAS

Se simula un circuito lineal, es un circuito mixto con cuatro resistencias en paralelo y corriente conectadas a dos fuentes de voltaje de corriente directa.

![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/Circuitoo1.jpg)


Comprobación del Teorema de Thévenin

![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/circuito%202.jpg)





## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 2       | Fuente de Voltaje C.D.  |
| 2       | Multímetros digital  |
| 1       | Resistor de 560 kΩ   |
| 1       | Resistor de 4.7 kΩ   |
| 1       | Resistor de 330 Ω  |
| 1       | Resistor de 100 Ω|
| 1       | Resistor de 1 kΩ|
| 1       | Protoboard                    |

## 6. MAPA DE VARIABLES 

Variables eléctricas: 

* Voltaje
* Corriente 
* Resistores


## 7. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 
El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Fundamentalmente los prerrequisitos que requiere este laboratorio sería: un dispositivo tegnológico (sea un teléfono, una pc, un tableta, entre otras); pues trabajamos en un simulador online, nuestro segundo requisito es acceso a internet y finalmente tener conocimientos básicos sobre las leyes aplicadas, los componentes, elementos y variables que se utiliza para la creación y el siguiente análisis del circuito.

**ANÁLISIS DE RESULTADOS Y CÁLCULO DEL ERROR**

VALORES DEL CIRCUITO EQUIVALENTE DE THÉVENIN

* **VTH (V)**

| CALCULADO | MEDIDO  | 
|----------|------|
| 5.06 V | 5.0556 V |

* **RTH Ω**

| CALCULADO | MEDIDO  | 
|----------|------|
| 299 Ω | 298.86 Ω |

COMPROBACIÓN DEL TEOREMA DE THÉVENIN 

 * **CIRCUITO ORIGINAL**

* VOLTAJE (V)

| CALCULADO | MEDIDO  | 
|----------|------|
| 4.22 V | 3.9 V |

* CORRIENTE (mA)

| CALCULADO | MEDIDO  | 
|----------|------|
|  4.22 mA | 3.9 mA |

* **CIRCUITO EQUIVALENTE DE THÉVENIN**

* VOLTAJE (V)

| CALCULADO | MEDIDO  | 
|----------|------|
|  3.84 V | 3.89 V |

* CORRIENTE (mA)

| CALCULADO | MEDIDO  | 
|----------|------|
|  3.84 mA| 3.89 mA  |

- **CÁLCULO DEL ERROR DEL VOLTAJE DE THÉVENIN**

Voltaje calculado= 5.06 V

Voltaje medido= 5.0556 V

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=((5.06 V - 5.0556 V)/ 5.06 V )* 100

%error= 0.087 % 


- **CÁLCULO DEL ERROR DE LA RESISTENCIA DE THÉVENIN**

Resistencia calculada= 299 Ω 

Resistencia medida= 298.86 Ω 

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=(( 299 Ω - 298.86 Ω )/ 299 Ω )* 100

%error= 0.047 % 

- **CÁLCULO DEL ERROR DEL VOLTAJE EN R5 EN EL CIRCUITO ORIGINAL**

Voltaje calculado= 4.22 V

Voltaje medido= 3.9 V

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=((4.22 V - 3.9 V)/ 4.22 V)* 100

%error= 7.58 % 

- **CÁLCULO DEL ERROR DE LA CORRIENTE EN R5 EN EL CIRCUITO ORIGINAL**

Corriente calculado= 4.22 mA

Corriente medido= 3.9 mA

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=((4.22 mA - 3.9 mA)/ 4.22 mA)* 100

%error= 7.58 % 

- **CÁLCULO DEL ERROR DEL VOLTAJE EN R5 EN EL CIRCUITO EQUIVALENTE DE THÉVENIN**

Voltaje calculado= 3.84 V

Voltaje medido= 3.89 V

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=(|(3.84 V - 3.89 V)|/ 3.84 V )* 100

%error= 1.30 % 

- **CÁLCULO DEL ERROR DE LA CORRIENTE EN R5 EN EL CIRCUITO EQUIVALENTE DE THÉVENIN**

Voltaje calculado= 3.84 mA

Voltaje medido= 3.89 mA

%error=(|(Valor teórico-Valor medido)|/Valor teórico)* 100

%error=(|(3.84 mA - 3.89 mA)|/ 3.84 mA )* 100

%error= 1.30 % 


## 9.APORTACIONES

Para complementar la correcta cuantificacion de valores calculados y valores medidos se baso en videos de la plataforma online YouTube, y se implemento el circuito en el simulador multisim para confirmar los valores.

## 10. CONCLUSIONES

Por medio de este laboratorio hemos comprobado de una forma tanto teórica como práctica la funcionalidad del teorema de Thévenin el cual es de grna utilidad ya que nos ayuda a reducir un circuito complejo en uno mucho más sencillo para medir corriente o voltaje en algún elemento del circuitos. 

También corroboramos que la resistencia e intensidad calculadas por Thevenin son muy similares a las calculadas mediante las leyes de Kirchhoff.

Habiendo simulado y creado el circuito, podemos meditar que aunque hemos calculado los datos de una manera distinta, hemos podido comprobar que este método es valido y muy efectiva para los calculos buscados.

Con esto se puede concluir, que los datos finales muestran una pequeña diferencia entre los valores medidos y calculados, y se podría dar esto de de la differencia por dos razones : al momento de calcular con el multímetro los valores, intervienen las tolerancias de las resistencias, y esto podría afectar a los valores obtenidos; mientras que en los valores medidos tal vez intervenga el hecho que no habiamos usado todos los decimales presentados en la calculadora, la cual aunque poco afecta los valores obtenidos. 



## 11. RECOMENDACIONES

Recomendamos que se debe asegurarse de tomar cálculos de una manera clara y ordenada,para asi no equivocarse en el hecho remplazar y tener como consecuencia un % de error excesivo. En este caso especificamente, se debe en tener en cuenta de desconectar las fuentes de poder paso segundo y tercer caso respectivamente.

Se debe tener en mente, de si se equivoca al traducir el circuito teorico al simulador esto podria causarle problemas en sus calculos, entonces recomendable siempre calcular tus datos manualmente y de ahi proceder a ser el circuito simulado.

Para terminar, sugerimos acordarse para calcular el voltaje de una region se le conecta al circuito directamente y para calcular intensidad se debe tratar al multimetro como un elemento del circuito y conectarle en serie.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/CRONOGRAMA%205.png)

https://trello.com/b/UU1g7qMS/cronograma

## 13. BIBLIOGRAFÍA

* carakenio73. (10 de Noviembre de 2019). dademuchconnection. Obtenido de https://dademuch.com/2019/11/10/teorema-de-thevenin-analisis-de-circuitos-electricos/

* XNOMIND. (07 de Noviembre de 2019). Teorema. Obtenido de https://www.teorema.top/teorema-de-thevenin/#Pasos_para_aplicar_el_teorema_de_Thevenin



## 14.- ANEXOS
https://github.com/BriandaLema/Laboratorio5/blob/master/Anexos/ANEXOS%20LABORATORIO%205.pdf






