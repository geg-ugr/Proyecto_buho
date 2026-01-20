# Carretes de Helmholtz
## 1. Objetivo

El objetivo de esta práctica es entender y comprobar el mecanismo de inducción electromagnética debido a un campo magnético variable con el tiempo. Para ello se estudiará la relación entre el campo magnético creado por una bobina (denominado primario, a través de la corriente que circula por ella) y el voltaje inducido en otra bobina (denominado secundario) situado en su interior. Este voltaje inducido depende de varios parámetros: la frecuencia del campo magnético creado por el primario, la intensidad del campo magnético, y el número de vueltas de las bobinas. Usando este fenómeno se obtendrá una estimación del valor de la permeabilidad magnética del vacío, $\mu_0$.

## 2. Material empleado

* Generador de funciones.
* Solenoide primario.
* Solenoides secundarios, con diferente longitud y número de vueltas.
* Osciloscopio.
* Cables de conexión.

## 3. Fundamento

### 3.1 Campo magnético en el interior de una bobina por la que circula una corriente

Sea una bobina de longitud $L$ y $N$ vueltas ($n=N/L$ es su número de vueltas por unidad de longitud). Si suponemos que la bobina es muy larga comparada con el radio de las espiras que la forman, el campo magnético en su interior es aproximadamente uniforme y paralelo al eje de la bobina, y aproximadamente nulo fuera de esta. Bajo esta aproximación, dada la simetría del problema, podemos calcular el campo $\vec{B}$ usando la ley de Ampere:

$$
\begin{equation}
\oint_C \vec{B}\cdot d\vec{l} = \mu_0 I^*
\tag{1}
\end{equation}
$$


donde el primer miembro, es la circulación del campo magnético a lo largo de un camino cerrado $C$, $I^*$ es la intensidad total que atraviesa una superficie que se apoya en dicho camino y $\mu_0$ es la permeabilidad magnética del vacío.

Para la aplicación de la Ley de Ampere, tomamos el camino rectangular C (de vértices 1, 2, 3, 4) que se muestra en la figura siguiente:

![Figura 1](./figures/permeabilidad_1.png)

A la integral de la ecuación (1) a lo largo del camino $C$ solamente contribuye el tramo 1-2, ya que en los tramos 2-3 y 4-1 el campo es perpendicular al camino, y en el 3-4, que discurre por el exterior de la bobina, el campo es cero (de acuerdo con la suposición de bobina larga con respecto a su radio). Además, el campo es constante a lo largo del camino 1-2 y paralelo a $d\vec{l}$,  por lo que

$$
\begin{equation}
\oint_C \vec{B}\cdot d\vec{l} = Bl = \mu_0 I^*
\tag{2}
\end{equation}
$$

Dado que hay $N$ espiras en la longitud total $L$ de la bobina, en un tramo de longitud $L$ hay $Nl/L$ espiras. Como cada espira trasporta una corriente de intensidad $I$, la corriente que atraviesa el camino cerrado $C$ es $I^*=NlI/L=nLI$. Sustituyendo el valor de  $I^*$ en la ecuación (2) se obtiene:

$$
\begin{equation}
bl = \mu_0 I^* = \mu_0nlI
\tag{3}
\end{equation}
$$

donde puede comprobarse que $B$ no depende ni de la longitud de la bobina ni de su diámetro, sino únicamente de la corriente que pasa por las espiras y lo juntas que éstas estén, es decir el número de espiras por unidad de longitud, $N$.

Particularizando la expresión (3) para el caso de una intensidad $I(t)$ sinusoidal de la forma $I(t) = I_0 \cos(\omega t)$, se obtiene:

$$
\begin{equation}
B(t) = \mu_0 n I_0 \cos(\omega t)
\tag{4}
\end{equation}
$$

## 4. Posibles tareas

## 5. Posibles mejoras

## 6. Necesidades y fabricación
