# Práctica 4
# *TEOREMA DE SUPERPOSICIÓN*
## *PLANTEAMIENTO DEL PROBLEMA*
Se han observado diferentes técnicas para la resolución de circuitos, entre ellos el análisis nodal y el análisis de mallas, todo esto bajo la aplicación de las Leyes de Kricchoff y la Ley de Ohm. Pero cuando en un circuito encontramos más de dos fuentes de voltajes, ya sea de corriente, de voltaje o ambas, el cálculo de voltaje o corriente en cada uno de sus componentes resulta ser mucho más complicado. Es por esto que surge una nueva técnica, el teorema de la Superposición, del cual queremos conocer que tan efectivo es y para esto también tendremos que comprobarlo.

## *OBJETIVO:*
Comprobar experimentalmente el Teorema de Superposición, mediante la comapración de los resultados teóricos junto con los prácticos simulados en los laboratorios virtuales para clarificar los conceptos respecto a esta técnica.


## *LISTA DE MATERIALES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 2  | Fuente de voltaje de C.D. |
| 2  | Multímetros digitales |
|  1 | Resistor de 1k  |
|  1 | Resistor de 2.2k  |
|  1 | Resistor de 820k  |
|  1 | Resistor de 470k  |
| 1  | Protoboard      |

## *MARCO TEÓRICO*
El teorema de la superposicion se puede utilizar tanto en AC como en DC , para poder determinar si se puede aplicar este método debemos tomar en cuenta que solo es aplicable para circuitos lineales , que estan conformados por componentes en las cuales la corriente es directamente proporcional a la tensión de sus terminales.

Este método nos ayuda a calcular tanto como voltajes , intensidades en las cuales halla varias fuentes de energía (fuentes de voltaje, fuentes de corrientes) y para obtener el resultado de este procedimiento se puede hallar sumando la tensión del circuito a cada una de las fuentes (independientes) por separado.

Fig 1.

Los pasos a seguir son los siguientes:

1) Se quitan las todas las fuentes excepto una, tomar en cuenta que si anulamos un voltaje este se convierte en corto circuito y si anulamos una corriente se hace un circuito abierto

Fig 2.


Fig 3.


2) Se calcula el voltaje y intensidades solo con la fuente que no se quito.

3) Se repiten los pasos 1 y 2 con cada fuente.

4) Se suman las respuestas de cada fuente (Tomar en cuenta los signos con lo que se desplaza la corriente , en algunos casos puede restarse)



## *PROCEDIMIENTO*
1. Implemente el siguiente circuito que se muestra en la figura:

![alt text](https://github.com/Kevi7k/Practica4/blob/master/Img/Diagrama%201.jpg)
Fig.4. Circuito para comprobar el teorema de Superposición

2. Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

3. Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

4. Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

## *TABULACIÓN DE DATOS*

|Tipo de dato|Voltaje Total (Va)| Voltaje (Va)cuando V2=0 |RVoltaje (Va)cuando V1=0|
| ------------- | ------------- | ------------- | ------------- |
| Calculado | 999 | 999 | 999 |
| Medido | 999 | 999 | 999 |

TABLA I. Medición de voltaje aplicando superposición

|Tipo de dato|Corriente Total (Va)| Corriente (Ix) cuando V2=0 |Corriente (Ix) cuando V1=0|
| ------------- | ------------- | ------------- | ------------- |
| Calculado | 999 | 999 | 999 |
| Medido | 999 | 999 | 999 |

TABLA II. Medición de corriente aplicando superposición

## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ralizará una tabla donde se muestre  el error relativo de cada valor obtenido:
|NODO| Resultados Analíticos |Resultados Experimentales|%Error|
| ------------- | ------------- | ------------- | ------------- |
| 1  |  00 | 00 | 0%|
| 2  | 00| 00 | 0% |

## *DIAGRAMA*

![alt text]()

Fig.5. Circuito Simulado en DCAClab

![alt text]()

Fig.6. Circuito Simulado en TinkerCAD

## *ECUACIONES*

Utilizamos principalmente laley de Ohm, conociendo que su fórmula es I=V/R

donde: 

       Intensidad de Corriente=Amperio (A)

       Voltaje=Voltio (V)

       Resistencia= Ohmio (omega)


## *EXPLICACIÓN DEL CIRCUITO*


## *CONCLUSIONES*

- 

## *RECOMENDACIONES*

- Es necesario asegurar los valores que asignamos tanto a las fuentes de voltaje como a las resistencias, ya que se suele cometer errores con las unidades de medida, de igual forma que la conexión esté bien hecha para que las mediciones sean lo más exactas posibles.

- Llevar claro el concepto de esta ley de nodos, para realizar de manera correcta la práctica.

- Tomar en cuenta sobre el peligro que puede ocasionar estos voltajes y la mala utilización de las resistencias.

- Para el cálculo de corrientes y voltajes, debemos realizar bien la conexión de nuestro multímetro, ya que, si no lo colocamos bien, podemos quemarlo y nos empezará a dar resultados erróneos.

## *CRONOGRAMA*

![alt text]()

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*

![alt text]()

Fig. 7. Medicones




