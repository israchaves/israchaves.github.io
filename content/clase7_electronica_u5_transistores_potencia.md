<style>
.reveal section img { background:none; border:none; box-shadow:none; }


#left {
    margin: 10px 0 15px 20px;
    text-align: center;
    float: left;
    z-index:-10;
    width:48%;
    font-size: 0.85em;
    line-height: 1.5;
}
#right {
    margin: 10px 0 15px 0;
    float: right;
    text-align: center;
    z-index:-10;
    width:48%;
    font-size: 0.85em;
    line-height: 1.5;
}

</style>



# Unidad 5: Tipos de transistores


<span style="font-size: 20.0pt; "> **Profesor:** Ing. Israel Chaves Arbaiza </span>

<span style="font-size: 20.0pt;"> **Curso**: Electrónica Básica para Ing. Mecánica  </span>


<img align="left" width="300" height="300" src="images/logo-ucr.png">

<img align="right" width="400" height="250" src="images/logoEIM.png">

---
## Agenda

<span style="font-size: 22.0pt; ">

* Transistor de Monounión
* Rectificador Controlado de Silicio
* Diodo Shockley
* DIAC
* TRIAC
* Ejemplos

</span>


---
## Transistor Monounión UJT


<span style="font-size: 22.0pt; ">

Cuenta con **una sola unión NP**, y es útil ya que **absorbe poca potencia**. Se puede aplicar en:

* Osciladores
* Controles de fase
* Temporizadores
* Circuitos de disparo
* Fuentes reguladas por corriente o voltaje


<img  width="400" height="250" src="images/ujt00.png">


</span>


---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">

El UJT es un dispositivo de tres patillas.

Una pastilla de material de silicio **tipo N** levemente dopada (
resistencia incrementada) tiene dos contactos base fijados a los dos
extremos de una superficie y una barra de aluminio ligada a la superficie
opuesta.

La unión tipo p-n se forma en el límite de la barra de aluminio y la
pastilla de silicio tipo n

<img  width="400" height="280" src="images/ujt.png">

</span>

---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">

El circuito equivalente del UJT equivale a dos resistores (uno fijo y
uno variable) y un diodo único.
La resistencia $R_{B1}$ se muestra como un resistor variable puesto que
su magnitud variará con la corriente $I_E$


<img  width="500" height="350" src="images/ujt01.png">
</span>

---
## Transistor Monounión UJT

<span style="font-size: 22.0pt; ">

Para un transistor de monounión representativo, $R_{B1}$ , puede variar
de $5 k\Omega$ a $50 \Omega$ por un cambio correspondiente de $I_E$ a partir de $0 \mu A$ a $50
\mu A$.
La resistencia entre las bases $R_{BB}$ es la resistencia del dispositivo
entre las terminales $B_1$ y $B_2$ cuando $I_{E} = 0$.



<img  width="600" height="400" src="images/ujt05.png">


</span>


---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">

En general, $R_{BB}$ oscila de $4 k\Omega$ a $10 k\Omega$.
La posición de la barra de aluminio determinará los valores relativos
de $R_{B1}$ y $R_{B2}$ con $I_{E}= 0$.
La magnitud de $V_{R_{B1}}$ (con $I_{E}= 0$) la determina la regla del divisor de
voltaje.
La letra griega $\eta (eta)$ denota la relación de retiro intrínseca del
dispositivo.

<img  width="600" height="300" src="images/ujtec02.png">

</span>

---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">

En potenciales de emisor aplicados, $V_E$, mayores a la suma de $V_{R_{B1}}$
(= $\eta V_{BB}$ ) y la caída del voltaje directa del diodo $V_D$ (0.35 $\rightarrow $0.70 V) el diodo se encenderá.
El potencial de encendido es

$$
V_{P}=\eta V_{BB} + V_D
$$

</span>

---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">

Las características de un transistor de monounión representativo se
muestran para un valor fijo de $V_{BB}$.
Para potenciales de emisor a la izquierda del punto pico, la
magnitud de $I_E$ nunca es mayor que la corriente del emisor en corte $I_{EO}$ ($\mu A$).

<img  width="700" height="380" src="images/ujt02.png">
</span>

---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">

La corriente $I_{EO}$ corresponde casi a la corriente de fuga en inversa
$I_CO$ del transistor bipolar convencional. A esta región, se le llama la **región de
corte**
Una vez establecida la conducción en $V_{E} = V_{P}$ , el potencial del
emisor $V_E$ se reducirá al incrementarse $I_E$

<img  width="700" height="380" src="images/ujt02.png">
</span>

---
## Transistor Monounión UJT

<span style="font-size: 20.0pt; ">
$I_{EO}$ ($mA$) no se muestra puesto que la escala horizontal está en
miliamperes.
La intersección de cada curva con el eje vertical es el valor
correspondiente de $V_P$ . Para valores fijos de $\eta$ y $V_D$ , la magnitud de $V_P$
variará como $V_{BB}$ .

<img  width="700" height="300" src="images/ujt04.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 18.0pt; ">

Presentado por *Bell Telephone Laboratories* en 1956; se utiliza para controlar la activación de dispositivos, **a manera de interruptor**. 
Han sido diseñados para **controlar potencias altas**, como 10 MW, con valores nominales individuales hasta de 2000 A a 1800 V. 
Su intervalo de frecuencia de aplicación ronda los 50 kHz, lo que permite que se utilice para calefacción por inducción ó limpieza ultrasónica. 

<img  width="700" height="300" src="images/scr00.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 20.0pt; ">

El SCR es un rectificador, construido de silicio con una tercera terminal para propósitos de control. 
Se escogió el silicio por sus altas capacidades de temperatura y potencia. 
La tercera terminal, llamada **Compuerta** , determina cuándo el rectificador cambia de abierto a cortocircuito. 

<img  width="600" height="300" src="images/scr01.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 18.0pt; ">

En la región de conducción, cuando está en cortocircuito, la resistencia dinámica del SCR está entre los $0,01 \Omega$ y los $0,1 \Omega$.
Por el contrario, la resistencia inversa, suele ser de $100 k\Omega$ ó más. 
Para que se establezca la conducción directa: 
1. Se debe aplicar un pulso de magnitud suficiente a la compuerta, para establecer el encendido en la compuerta. 
2. El ánodo debe tener un voltaje positivo respecto al cátodo, y la corriente debe ingresar por el ánodo. 

<img  width="600" height="200" src="images/scr02.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 20.0pt; ">

El circuito equivalente del SCR, se representa con 2 transistores BJT, uno de tipo PNP y el otro tipo NPN. 

<img  width="700" height="400" src="images/scr04.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 20.0pt; ">

Su comportamiento, incluyendo el disparo, se observa en la siguiente imagen: 

<img  width="800" height="400" src="images/scr05.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 20.0pt; ">
Los tiempos de encendido de un SCR, varían según las corrientes que controle:

* Para dispositivos de baja potencia, los tiempos de encendido típicos rondan de $0,1 \mu s$ a $1 \mu s$

* Mientras que para corrientes entre 100 A y 400 A, pueden tener tiempos de 10 a 25 $\mu s$

<img  width="600" height="200" src="images/scr03.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 18.0pt; ">

Para apagar el SCR, la única manera es quitar la corriente del Ánodo, para ello existen 2 métodos:
1. **Interrupción de corriente en el ánodo**, donde por algún tipo de interruptor, se quita la corriente que entra al ánodo. 
2. **Conmutación forzada**, acá el interruptor se ubica en paralelo al SCR, en lugar de ubicarlo en serie. Este método es el preferido, más eficiente y seguro. 

<img  width="600" height="300" src="images/scr07.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 20.0pt; ">

Las gráficas de comportamiento del SCR, con y sin disparo, se muestran a continuación:

<img  width="800" height="400" src="images/scr08.png">

</span>

---
## Rectificador Controlado de Silicio SCR

<span style="font-size: 20.0pt; ">


<iframe  width="580" height="500" src="https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgoqoQFMBaMMAKACcRs8AWcQqrr2KEoySCwBKnHiGHTeeKkpDdaopdAQsAzvJAo8ePdkJGqEAGYBDADba6OzghT6EIlG9cjzIa3YccHiJgGO6eQaJgcJJe4KGxYAbqKmrKMFoA5samxjJKLCHkgnwCOQZmIAzc0NzE3GAEiiYEhNjYGIxg2JXVtfWNkM1EbR1M3TCQEBP4LpQsQA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</span>

---
## Diodo Shockley

<span style="font-size: 20.0pt; ">

Es un diodo **PNPN** de cuatro capas, pero con sólo dos terminales externas. 
Sus características son las mismas que el SCR, pero con $I_G = 0$

El dispositivo estará en abierto (*apagado*) hasta que se alcance su voltaje de conducción, en ese momento, entra en cortocircuito (*encendido*)

<img  width="800" height="300" src="images/shockley.png">

</span>

---
## Aplicación de Shockley como interruptor

<span style="font-size: 20.0pt; ">

Comúnmente, el Shockley se usa como interruptor de disparo para un SCR. 

Cuando se energiza el circuito, el voltaje en el capacitor comienza a cargarlo, hasta llegar al voltaje necesario para activar el diodo; y en consecuencia, se dispara el SCR. 

<img  width="400" height="250" src="images/shockley2.png">

</span>

---
## DIAC

<span style="font-size: 20.0pt; ">

Es una combinación inversa en paralelo de dos terminales de capas semiconductoras que permiten la activación ó disparo en cualquier dirección. 

Se puede aprovechar al máximo la condición de encendido en cualquiera de las dos direcciones en aplicaciones de CA.

<img  width="800" height="300" src="images/diac.png">

</span>

---
## DIAC

<span style="font-size: 20.0pt; ">

Ninguna de las capas se designa como cátodo, cuando el ánodo 1 es positivo respecto al ánodo 2, el ánodo 2 se comporta como cátodo, y viceversa. 

<img  width="650" height="300" src="images/diac2.png">

</span>

---
## DIAC

<span style="font-size: 20.0pt; ">

Los voltajes de ruptura son muy parecidos en cuanto a magnitud, pero pueden variar desde un mínimo de 28 V y hasta un máximo de 42 V. 

Los niveles de corriente ($I_{BR1}$ e $I_{BR2}$) también son de magnitud muy parecida para cada dispositivo. 

<img  width="650" height="300" src="images/diac3.png">

</span>

---
## TRIAC

<span style="font-size: 20.0pt; ">

Es básicamente un DIAC con una terminal de compuerta para controlar el encendido, ó lo que es igual, un SCR que puede trabajar en cualquiera de los semiciclos de CA.

<img  width="650" height="300" src="images/triac.png">

</span>

---
## TRIAC

<span style="font-size: 20.0pt; ">


<img  width="650" height="450" src="images/triac_curve.png">

</span>

---
## Aplicación común: Control de fase (potencia)

<span style="font-size: 20.0pt; ">

Acá se controla la potencia de CA suministrada a la carga encendiéndose y apagándose durante las regiones positiva y negaiva de la señal senoidal de entrada. 

La acción de este circuito durante la parte positiva de la señal de entrada es muy parecida a la encontrada por el diodo Shockley. 

<img  width="650" height="300" src="images/triac4.png">

</span>

---
## Aplicación común: Control de fase (potencia)

<span style="font-size: 20.0pt; ">

La ventaja de esta configuración es que durante la parte negativa de la señal de entrada se obtendrá el mismo tipo de respuesta ya que tanto el DIAC como el TRIAC se pueden encender en la dirección inversa. 

Si se ajusta el R, podemos controlar el ángulo de conducción. Existen unidades disponibles capaces de manejar cargas de más de 10 kW. 

<img  width="650" height="300" src="images/triac4.png">

</span>

---
## Ejemplo DIAC y TRIAC

<span style="font-size: 20.0pt; ">


<iframe  width="580" height="500" src="https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcAmWDLMgZgBxmcgCxg4CcS6IFkVApgLRhgBQA5uFgGw0LI4fcqhQlCjMA7ik4jkAdmQCachZGYAnKTPmaQhLCvCRO+deBJaF+aSGWi5qgEpmcFs1xvaaEQWE6lospAInHKELrKyYCI0MdAIzJicih6WWPhUfKIwkExQsJD8YHAgAC5qAK60zADGOnqWyNa8-LHwcBD0hNCkpJCECIHBQZCBpHntbDrNU8JZCdh1+hyZ9aLoXm1tIFitLAD2utsGYZyyR7EtNodYzLhXAGIQG0qYxYwgAAoAFgCGAM60AA6fwAwnsAHZlPYAG2YQA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</span>

---
## Notas importantes

<span style="font-size: 20.0pt; ">

* Los temas de la unidad 5 se pueden encontrar en el capítulo 11 del Floyd
* Revisar especialmente los ejemplos 11-2, 11-3, y 11-4

</span>


---
## Ejemplo 1

<span style="font-size: 20.0pt; ">

Explique el funcionamiento de este circuito. 

<img  width="750" height="400" src="images/ejemplo_u5.png">

</span>

---
## Ejemplo 2

<span style="font-size: 20.0pt; ">

¿Cuál es la reacción del motor cuando se presionan las botoneras 1 y 2? Explique

<img  width="750" height="400" src="images/ejemplo_u5_1.png">

</span>

---
## Ejercicio 1

<span style="font-size: 20.0pt; ">

¿Cuál sería la medición instantánea del amperímetro en cada caso?

<img  width="450" height="400" src="images/ejercicio_u5.png">

</span>

---
## Ejercicio 2

<span style="font-size: 20.0pt; ">

¿Cuál es el valor mayor de la resistencia R para que el SCR no se abra?

<img  width="650" height="400" src="images/ejercicio_u5_1.png">

</span>