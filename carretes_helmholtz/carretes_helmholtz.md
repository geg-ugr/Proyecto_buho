# Carretes de Helmholtz
## 1. Objetivo

El objetivo de esta práctica es el estudio del campo magnético creado por unos carretes de Helmholtz a lo largo de su eje. 

## 2. Material empleado

* Fuente de tensión de corriente continua. 
* Carretes de Helmholtz situados sobre un soporte móvil. 
* Amperímetro. 
* Teslámetro con sonda Hall longitudinal (axial). 
* Regla graduada. 
* Cables de conexión. 

## 3. Fundamento

Supongamos dos bobinas formadas, cada una de ellas por N espiras de radio a separadas por una distancia d, como se muestra en la figura siguiente, siendo I_1 e I_2 las corrientes estacionarias que circulan respectivamente por las bobinas 1 (situada en z=-d/2) y 2 (situada en z=d/2).  

![Figura 1](./figures/carretes_1.png)

De acuerdo con la ley de Biot y Savart, el valor del campo magnético generado en cualquier punto situado en el eje z (ρ=0), que por simetría no depende de φ, es:

![Figura 1](./figures/carretes_2.png)

donde z es la distancia medida sobre el eje z tomando como origen el punto central en el eje de los dos carretes y se ha hecho la aproximación de considerar despreciable el espesor de las bobinas.
La expresión anterior para  B ⃗(ρ=0,z) puede particularizarse para los siguientes casos:

1. **Sentido de las corrientes antiparalelo (I_1=-I_2)**
Si z=0 e I_1=-I_2, B_z (z=0)=0. Aprovecharemos este hecho para localizar el punto central en el eje de los carretes, punto que tomaremos como referencia en la medida de longitudes

2. **Si z=0 e I_1=I_2=I**

![Figura 3](./figures/carretes_3.png)

En particular, si d=a

![Figura 4](./figures/carretes_4.png)

Este caso es de gran interés ya que es común utilizar esta configuración en experimentos en los que se desea generar un campo magnético uniforme dentro de una región determinada del espacio. Como ejemplo, la figura siguiente muestra una representación gráfica de las líneas de campo magnético para unos carretes en los que se cumple I_1=I_2=I y d=a en la que se observa una zona de campo bastante uniforme.

## 4. Posibles tareas

### Calibración de la sonda de campo magnético

Sea comprada o fabricada, antes de comenzar las mediciones de campo magnético la sonda debe calibrarse. Para ello se comparan una serie de valores de campo medidos en xxx con respecto a los valores que deberían obtenerse conocida la expresión teórica del campo en ese mismo punto

### Obtención de una región de campo uniforme en la dirección del eje entre las bobinas

Utilizando un par de bobinas se puede conseguir una región entre estas en las que el campo sea uniforme.

## 5. Posibles mejoras

### Obtención de una región de campo uniforme en una dirección del plano

Utilizando dos pares de bobinas cuyos ejes sean perpencilares entre sí se puede obtener un campo uniforme en cualquier dirección contenida en el plano que contiene los ejes de las bobinas

## 6. Necesidades y fabricación

### Carretes

#### Soporte

El soporte debe:
1. tener algún sistema o muesca que permita comenzar a enrollar la bobina,
2. rígido para permitir la tensión de la bobina al enrollarla sin deformarse,
3. de un material que soporte un cierto aumento de temperatura si por las bobinas circula más corriente de la deseada

#### Bobina

Idealmente, que puedan producir un campo elevado sin necesidad de una gran corriente. Calcular el campo en función del número de vueltas y la corriente, y elegir la galga del cable más adecuada

### Sonda de campo magnético

*ToDo*