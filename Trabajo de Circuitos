# INFORME-DE-LABORATORIO-3

1) OBJETIVOS

Objetivo general:

Comprobar experimentalmente el Análisis de Nodos.

Objetivos especificos:

-Identificar el nodo de referencia del circuito, para realizar el análisis correcto de los nodos.

-Diseñar en algún simulador facilitado por el docente el esquema propuesto una tomar medidas de tensión en los nodos y verificar si sale lo mismo realizando teóricamente.

-Realizar la comparacion de datos de forma indirecta y directa de los nodos.

2) Marco teorico

El análisis de nodos se realiza mediante la aplicación de LCK, la cual es la ley de corrientes de Kirchhoff, ayuda a encontrar los voltajes de nodos del circuito. Para la construcción del sistema de ecuaciones, existe para una ecuación para cada nodo. Un nodo es cualquier punto en un circuito donde se encuentren conectados dos o más componentes, para su análisis se debe tener en cuenta que las corrientes que salen del nodo son positivas y las que entran son negativas.

Dependiendo el tipo de circuito y su forma se debe seleccionar un nodo de referencia:

•	Fuentes de corriente independientes

• Fuentes de corriente controladas

• Fuentes de voltaje independientes a tierra

• Fuentes de voltaje independientes flotantes

• Fuentes de voltaje controladas a tierra

• Fuentes de voltaje controladas flotantes


El método general que se aplica para el análisis de nodos, es el que tiene fuentes de corriente independientes y fuentes de voltaje independientes a tierra.

Pasos a seguir para el teorema de nodos:


-Asigna las tensiones a los nodos restantes y se asignan respecto al nodo de referencia.

-Se dibuja la trayectoria de corriente en cada rama, tratando de trazar trayectorias que vayan hacia el nodo de referencia o tierra.

-Después se debe aplicar LCK a cada uno de los nodos de no referencia, se utiliza la ley de ohm para expresar la corriente en las ramas en términos de las tensiones de los nodos.

-Resolver el sistema de ecuaciones de los nodos, el resultado será las tenciones de un nodo desconocido.

![](lab_3/MAPA_LAB_3.png)


3) Explicacion de procedimiento

El nodo 1 es el que se encuentra de la resistencia de 1.8 kohm y entre las resistencias en paralelo de 2.2kohm y 470 ohm, y el nodo numero dos es aque que termina en la ressitencia 2.2kohm y las resistencias en paralelo de 1.5kohm y  3.9kohm

Planteamos la ecuacion de I1=-I2-I3, por tal motivo que las intensidades o corrientes que salen son negativas y la que entra es positiva. Por lo tanto reescribimos la ecuacion en funcion de sus resistencias y voltajes.
 
Plantenado las ecuaciones para los dos nodos realizamos un sistema de ecuaciones para encontrar el voltaje.


![](lab_3/Analisis_circuito.jpg)


Cálculos:

I1+I2+I3=0
((V1-12)/1800)+(V1/470)+((V1-V2)/2200)=0
(V1-12)+V1(1800/470)+1800/2200 (V1-V2)=0
22(V1-12)+V1*3960/47+18(V1-V2)=0
1034(V1-12)+3960V1+846(V1-V2)=0
1034 V1-12408+3960 V1+846 V1-846 V2=0
▭1 5840 V1-846 V2=12408

I4+I5+I6=0
((V2-V1)/2200)+V2/3900+(V2-8)/1500=0
(V2-V1)+2200/3900 V2+2200/1500 (V2-8)=0
15(V2-V1)+330/39 V2+22(V2-8)=0
195(V2-V1)+110V2+286(V2-8)=0
195 V2-195 V1+110 V2+286 V2=2288
▭2 591 V2-195 V1=2288

Utilizando sistema de ecuaciones:
5840 V1-846 V2=12408          *(195)
-195 V1+591 V2=2288            *(584)

1138800 V1-164970 V2=2419560
-1138800 V1+3451440 V2=13361920
Sumando las dos expresiones:
3286470 V2=15781480
V2=4,8019 V
Reemplazando en ▭1
5840 V1-846(4,8019)=12408
5840 V1=846(4,8019)+12408
5840 V1=16470,45
V1=2,8202 V

![](lab_3/voltaje.jpeg)


Intensidad:

![](lab_3/intensida.jpeg)

Simulacion en Tinkercard:

![](lab_3/tinker_volta.jpeg)


4) Respuesta a interrogantes y cálculo de error.

Resultados:

![](lab_3/tabla.png)


Se logro comprabar que lso resutlados del modo simulado es igual a los valores que encontramos dentro de el analisis por LCK, los cuales fueron evaluados por un sistema de ecuaciones, y por lo tanto obtuvimos los voltajes en los nodos correspondientes al circuito planteado.

El calculo de error, si se lo evalua, este tendra un resultado de cero ya que corresponde a los valores exactos, tanto medidos, simulados y calculados.

5) Video

https://youtu.be/BDATG5Zll0w


6) Conclusiones.

-Diseñamos el circuito con la ayuda del simulador y ademas tomamos medidas de tensión en nodos y verificamos que salio lo mismo realizando de manera teórica como lo indica el cuadro.

-Se analizaron los circuitos en serie, con uso de las leyes de Ohm y Kirchhoff, así se lograron resolver los problemas en circuitos eléctricos.

-El calculo de los voltajes dentro de los nodos se utiliza para ver si el estado del circuito está abierto o cerrado, para no ocasionar cortocircuitos o caidas de voltaje.



7) Bibliografia

- M. (2021b, abril 2). Teorema de Nodos. MiElectrónicaFácil.com. Recuperado 1 de diciembre de 2021, de https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-nodos/#pasos-del-teorema-de-nodos

-Salazar, A. (2012). 3. Análisis Por Nodos Y Mallas 3.1. 35–62. http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf






