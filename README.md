# Informe_Laboratorio_5-

Integrantes: Chachalo Mayerli, Mensias Adrian, Rosero Andres

## **PRÁCTICA No.4 TEOREMA DE THÉVENIN**

## 1.  OBJETIVO DE LA PRÁCTICA

**Objetivo general** 

- Determinar de forma teórica y de forma experimental en un simulador para armar circuitos eléctricos los valores de voltaje y corriente de un circuito resistivo en el cual existen 2 fuentes de voltaje mediante el uso del teorema de Thévenin transformando un circuito complejo en uno más simple.

**Objetivos específicos**

- Diferenciar los valores calculados de los valores medidos y así ver el porcentaje de error que se puede evidenciar al usar el Teorema de Thévenin en la resolución de circuitos eléctricos.

- Realizar la simulación del circuito eléctrico en una aplicación virtual y observar el funcionamiento del circuito sin aplicar el teorema de Thévenin y de igual forma observar su funcionamiento al momento en el que se aplcia el Teorema de Thévenin.

## 2.  MARCO TEORICO

![image](https://user-images.githubusercontent.com/75383758/126709008-7cc3c0aa-4594-429c-9130-12a403628d29.png)

## 3.  EXPLICACION DEL PROCEDIMIENTO 

3.1 **REQUISITOS PREVIOS**

Para el circuito mostrado en la figura 5.1:
a) Determine el valor de voltaje y corriente en el resistor R5. Anote los resultados
en la tabla 5.2.
b) Obtenga los valores del circuito equivalente de Thévenin y anótelos en la tabla 5.1.

3.2 **NFORMACIÓN GENERAL**

Una de las maneras de simplificar y facilitar el análisis de circuitos eléctricos y
electrónicos es por medio del Teorema de Thévenin que establece que:
Un circuito eléctrico puede representarse con un circuito dual o equivalente,
representado por una sola fuente de voltaje en serie con una resistencia. El valor de la
fuente de voltaje se conoce como el “voltaje de Thévenin” y la resistencia en serie como
“resistencia de Thévenin”.

El voltaje de Thévenin (VTH) es el voltaje en circuito abierto entre las terminales
del circuito para el cual se requiere el equivalente de Thévenin.

La resistencia de Thévenin (RTH) es la resistencia equivalente vista de la terminal
del circuito para el equivalente de Thévenin, con las fuentes de alimentación en cero.


3.3 **MATERIAL Y EQUIPO REQUERIDO**

|**CANTIDAD**| **ELEMENTO**|
|:---: | :---: |
| 2 | Fuente de voltaje de C.D |
| 2 | Multimetros digitales |
| 1 | Resistor de 560 Ω |
| 1 | Resistor de 4.7 kΩ |
| 1 | Resistor de 330 Ω |
| 1 | Resistor de 100 Ω |
| 1 | Resistor de 1 kΩ |
| 1 | Protoboard |

3.4 **PROCEDIMIENTO**

3.4.1 Arme el circuito que se muestra en la figura 5.1

![image](https://user-images.githubusercontent.com/85126275/126195527-e7ff9bd9-00db-4782-9343-c2d449bb4299.png)

### Circuito armado en Tinkercad

![image](https://user-images.githubusercontent.com/85126275/126688725-c5c186c0-01f1-42d1-b095-706e9c9dccfa.png)

3.4.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/85126275/126689065-e15a7ea9-25b0-4631-a636-af1b3041fd07.png)

3.4.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/85126275/126689200-d40cdb4c-b82c-417c-bbe6-fb8113253a41.png)

3.4.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/85126275/126689314-40deeaf1-87d3-4096-b757-b2a6b0dd8074.png)

3.4.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

3.5 Procedimiento Analítico

![image](https://user-images.githubusercontent.com/85209614/126737500-e0479d35-f6b1-494e-9354-8f50814cc2b0.png)

![image](https://user-images.githubusercontent.com/85209614/126737587-7405c42e-a05f-41cf-893a-7a407d288411.png)

![image](https://user-images.githubusercontent.com/85209614/126737537-57b2425a-2368-491e-9bee-31391cbf4fef.png)

![image](https://user-images.githubusercontent.com/85209614/126737609-0df16302-e8d3-40ee-b6fd-156426f54815.png)

![image](https://user-images.githubusercontent.com/85209614/126738124-69491e59-7417-43d2-b8f9-41a8a1462479.png)

Circuito Thévenin

![image](https://user-images.githubusercontent.com/85209614/126738201-1570c09a-f0e7-43b8-bc87-a3504adaa66e.png)

Implementación de R_5

![image](https://user-images.githubusercontent.com/85209614/126738280-0ba749ca-98b4-418d-969d-851a7c919962.png)

![image](https://user-images.githubusercontent.com/85209614/126738894-cadd0f50-4436-42f3-a7b7-b26d8cafb70e.png)


 Tabla 5.1 Valores del circuito Equivalente de Thévenin
 
 |               |  **CALCULADO** | **MEDIDO** |
 |     :---:     |     :---:      |    :---:   |  
 |   **VTH (V)** |     5.056      |    5.06    |
 |  **RTH (Ω)**  |     298.85     |    299     |
 
 Tabla 5.2 Comprobación del teorema de Thévenin 
 
 | **PARÁMETRO ELÉCTRICO** |   **Circuito Original**  |               |  **Circuito Equivalente de Thévelin**  |                 |
 |        :---:            |          :---:           |     :---:     |             :---:                      |      :---:      |
 |                         |        Calculado         |    Medido     |              Calculado                 |      Medido     |
 |       Voltaje (V)       |          3.89            |    3.89       |                3.89                    |       3.89      |
 |     Corriente (mA)      |          3.89            |    3.89       |                3.89                    |       3.89      |
 
 3.6 Cálculo del Error
 
 ![image](https://user-images.githubusercontent.com/85209614/126739711-0354e4a9-0fb7-45f1-a9cc-3f1c61782198.png)
 
## 4.  VIDEO

https://youtu.be/z4PntRIQhXA

## 5.  CONCLUCIONES 

- El teorema de Thévenin nos ayuda a que en un ciruito lineal complejo en el cual se encuentran dos fuentes de voltaje, lo podemos sustituir con una fuente de voltaje equivalente de Thévenin (V_Th) y usar de la misma forma una eresistencia equivalente de Thévenin (R_Th).

- Al momento en el que creamos un circuito equivalente mas pequeño y simple de uno más grande y complejo, se nos peermite calcular de forma rápida el valor de voltajes, la corriente o hasta la potencia de un circuito una vez que se conecta una carga.

- El cálculo de los valores de voltaje y corriente en el circuito presentado en el laboratorio se lo pudo realizar con facilidad gracias a este teorema ya que para calcular el valor de una resistencia debemos realizar un corto circuito en la fuente de voltaje y para una fuente4 de corriente se debe reemplazar por un circuito abierto. 

## 6.  BIBLIOGRAFÍA

Robbins, A., & Miller, W. (2010). Análisis de circuitos eléctricos. Teoría y práctica [recurso electrónico]. Cengage Learning Editores, S.A. de C.V.

Teorema de Thevenin – Análisis de circuitos eléctricos. dademuchconnection. (2021). Retrieved 22 July 2021, from https://dademuch.com/2019/11/10/teorema-de-thevenin-analisis-de-circuitos-electricos/.

TEOREMA DE THEVENIN EXPLICADO PARA QUE LO ENTIENDAS. Teorema. (2019). Retrieved 22 July 2021, from https://www.teorema.top/teorema-de-thevenin/.

Log in. Lucid.app. (2021). Retrieved 22 July 2021, from https://lucid.app/lucidchart/82bb8b91-37f7-4e89-ac48-8b5c426937b9/edit?beaconFlowId=FD1DDAC0FB0015DD&page=0_0#.





