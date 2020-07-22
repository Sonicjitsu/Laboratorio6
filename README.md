# LABORATORIO # 06

TEMA: TEOREMA DE LA MÁXIMA TRANSFERENCIA DE POTENCIA
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Analizar experimentalmente el Teorema de máxima transferencia de potencia eléctrica.

**1,2.-ESPECÍFICOS**

* Determinar los factores que causan la discrepancia entre datos medidos y calculados.
* Establecer experimentalmente la respuesta de potencia de un circuito, cuando se somete a una carga óhmica variable.
* Graficar la curva de transferencia de potencia según los datos obtenidos en el laboratorio. 

## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito eléctrico, en un programa online denominado Tinkercad con la finalidad de experimentarel análisis mediante el Teorema máxima transferencia de potencia. Se crea el circuito utilizando dos resistencias en serie conectadas a una fuente directa, con ello se puede calcular la potencia después de analizar su voltaje e intensidad del circuito.


## 3. MARCO TEÓRICO 

**TEOREMA DE MÁXIMA TRANFERENCIA DE POTENCIA**

Con el teorema se busca determinar la potencia consumida por una resistencia en un circuito y cuál ha de ser el valor de dicha resistencia para que dicha potencia sea máxima. Graficamente tendremos un circuito equivalente de Thévenin o Norton para poder aplicar el teorema de la máxima tranferencia, en la imagen se puede observar como sería en el caso de circuito equivalente de Thévenin.
![](https://github.com/BriandaLema/Laboratorio6/blob/master/img/pic169.jpg)

La potencia disipada en RL se calcula de la siguiente forma, conociendo que por Ley de Watt la pontencia es P= IxV y que por Ley de Ohm V=IR o I=V/R:

![](https://github.com/BriandaLema/Laboratorio6/blob/master/img/1.png)

Entonces con la anterior deducción¿Para qué valor de RL será máxima la potencia?

![](https://github.com/BriandaLema/Laboratorio6/blob/master/img/2.png)

Como RN = RTH, también RL = RN Se dice que la resistencia que disipa Pmax entre dos terminales es la resistencia del circuito equivalente Thévenin o Norton.

En conclusión este teorema nos dice que: 
**"La potencia máxima será desarrollada en la carga cuando la resistencia de carga RL sea igual a la resistencia interna de la fuente Ri"**


*Importante: 
Cuando se solicita obtener la máxima transferencia de potencia, la resistencia de carga debe adaptarse a la resistencia interna en las fuentes de voltaje.

## 4. DIAGRAMAS

Se simula un circuito con dos resistencias en serie, una de ellas va a ser constante y las otra va a variar, están  conectadas a una fuente de voltaje de corriente directo.

![](https://github.com/BriandaLema/Laboratorio6/blob/master/img/Exquisite%20Albar.png)


## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 1       | Fuente de Voltaje C.D.  |
| 2       | Multímetros digital  |
| 1       | Resistor de 1.2 kΩ   |
| 1       | Resistor de 1 kΩ   |
| 1       | Resistor de 220 Ω  |
| 1       | Resistor de 470 Ω|
| 1       | Resistor de 1.5 kΩ|
| 1       | Resistor de 1.8 kΩ|
| 1       | Resistor de 680 Ω|
| 1       | Resistor de 820 Ω|
| 1       | Resistor de 2.2 kΩ|
| 1       | Resistor de 3.9 kΩ|
| 1       | Resistor de 4.7 kΩ|
| 1       | Protoboard                    |


## 6. MAPA DE VARIABLES 

Variables eléctricas: 

* Corriente 
* Resistores


## 7. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 
El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Fundamentalmente los prerrequisitos que requiere este laboratorio sería: un dispositivo tegnológico (sea un teléfono, una pc, un tableta, entre otras); pues trabajamos en un simulador online, nuestro segundo requisito es acceso a internet y finalmente tener conocimientos básicos sobre las leyes aplicadas, los componentes, elementos y variables que se utiliza para la creación y el siguiente análisis del circuito.

**ANÁLISIS DE RESULTADOS Y CÁLCULO DEL ERROR**

Parámetros Eléctricos del circuito

| RL (Ω) | Corriente medida (mA) | Voltaje medido (V) | Potencia calculada experimentalmente (W) | Potencia calculada teóricamente (W) |
|----------|------|----------|------|----------|
| 220  | 10.6 | 2.32 | 0.024549 | 0.024592 |
| 470  | 8.98 | 4.22 | 0.037918 | 0.0378956 |
| 680 | 7.98 | 5.43 | 0.043289 | 0.0433314 |
| 820  | 7.43 | 6.09 | 0.045216 | 0.0452487 |
| 1000 | 6.82 | 6.82 | 0.046488 | 0.0465124 |
| 1500 | 5.56 | 8.33 | 0.046296 | 0.0463148 |
| 1800  | 5 | 9 | 0.045 | 0.045 |
| 2200 | 4.41 | 9.71 | 0.042820 | 0.0428211 |
| 3900 | 2.94 | 11.5 | 0.033737 | 0.03381 |
| 4700 | 2.54 | 11.9 | 0.030379 | 0.030226 |



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

Para complementar la correcta cuantificacion de valores calculados y valores medidos se baso en videos de la plataforma online YouTube, y se implemento el circuito en el simulador multisim para calcular los valores de la potencia experimentales ya que el simulador tinkercad no nos ofrece esa opción

![](https://github.com/BriandaLema/Laboratorio6/blob/master/img/Multisim.jpg)

## 10. CONCLUSIONES



Con esto se puede concluir, que los datos finales muestran una pequeña diferencia entre los valores medidos y calculados, y se podría dar esto de de la differencia por dos razones : al momento de calcular con el multímetro los valores, intervienen las tolerancias de las resistencias, y esto podría afectar a los valores obtenidos; mientras que en los valores medidos tal vez intervenga el hecho que no habiamos usado todos los decimales presentados en la calculadora, la cual aunque poco afecta los valores obtenidos. 



## 11. RECOMENDACIONES

Recomendamos que se debe asegurarse de tomar cálculos de una manera clara y ordenada,para asi no equivocarse en el hecho remplazar y tener como consecuencia un % de error excesivo. 

Se debe tener en cuenta,  la correcta implementacion del circuitos y sus valores ya que de otra manera esto causaría un error en los calculos, entonces  es recomendable siempre calcular tus datos manualmente y de ahi proceder a realizar el circuito simulado.

Para terminar, sugerimos acordarse para calcular el voltaje de una region se le conecta al circuito en forma pararela y para calcular intensidad se debe tratar al multimetro como un elemento del circuito y conectarle en serie.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio6/blob/master/img/Cronograma6.png)

https://trello.com/b/IgDMHPw0/laboratorio-6

## 13. BIBLIOGRAFÍA

* Semeria, M. (2015). Los tres teoremas: Fourier-Nyquist-Shannon (No. 582). Serie Documentos de Trabajo. Obtenido de https://www.econstor.eu/handle/10419/130833

* Máxima transferencia de potencia. (s.f). ANÁLISIS DE CIRCUITOS Y SISTEMAS LINEALES. Universitas Miguel Hernández. Obtenido de http://repositorio.innovacionumh.es/Proyectos/P_19/Tema_1/UMH_09.htm


## 14.- ANEXOS
https://github.com/BriandaLema/Laboratorio6/blob/master/Anexos/ANEXOS_lab6.pdf






