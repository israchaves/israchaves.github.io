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


# Unidad 3: Sistemas de Control


<span style="font-size: 20.0pt; "> **Profesor:** Ing. Israel Chaves Arbaiza </span>

<span style="font-size: 20.0pt;"> **Curso**: Mecatrónica  </span>


<img align="left" width="300" height="300" src="images/logo-ucr.png">

<img align="right" width="400" height="200" src="images/logoEIM.png">

---
## Agenda

<span style="font-size: 22.0pt; ">

* Control en la mecatrónica
* Métodos y tipos de control
* Modelado de sistemas mecatrónicos
* Análisis de respuestas de sistemas 
* Principios de optimización 

</span>

Note: Prueba de notas para el speaker

---
## Control en la mecatrónica


<span style="font-size: 22.0pt; ">


<img  width="900" height="280" src="images/control01.png">

</span>

----
## Control en la mecatrónica


<span style="font-size: 22.0pt; ">

* Típicamente, el sistema de control consta del sistema computacional que da órdenes a los actuadores
* En **Control Automático**, se conoce como *función de costo*, a la función que describe el rendimiento del sistema 
* Por ejemplo, medición del error, de la potencia consumida, desviación de un valor de referencia, etc. 
* Formalmente, el control debe diseñarse de manera que se cumpla el proceso deseado, minimizando la función de costo.

</span>

----
## Control en la mecatrónica


<span style="font-size: 22.0pt; ">

Para mejorar/diseñar un buen sistema, idealmente, se debe **optimizar** cada etapa del sistema, de manera que al unir las partes, luego de algunos ajustes. se cuenta con un subsistema optimizado.


<img  width="700" height="300" src="images/control02.png">

</span>

----
## Control en la mecatrónica

<span style="font-size: 22.0pt; ">


Sin embargo, en la práctica, muchas veces no podemos optimizar cada etapa del sistema. Por lo tanto, se optimiza el control (hardware o software)


<img  width="700" height="300" src="images/control03.png">

</span>


---

## Métodos y tipos de control


<span style="font-size: 22.0pt; ">

Formalmente, podemos hablar de 3 elementos clave en los tipos de control: 

1) **Control PID:** En un control a lazo cerrado, se mide el error entre un valor deseado y la salida del sistema. El control PID busca corregir y minimizar ese error. Para ello, utiliza 3 parámetros: **P (proporcional)**, ejecuta la acción para corregir el error, proporcionalmente al error, entre más grande sea, más grande P. 

**I (integral)**, considera el tiempo que ha permanecido presente el error. Entre más tiempo lleve el error presente en el sistema, más grande será I. Y por último, **D (derivativo)**, relacionado al cambio del error en el tiempo, es decir, entre más rápido cambie el error, mayor será D.  


</span>

----
## PID

<span style="font-size: 22.0pt; ">

<img  width="700" height="300" src="images/pid.png">


</span>

----
## PID

<span style="font-size: 22.0pt; ">

<img  width="700" height="300" src="images/horno.jpg">


</span>

----
## PID

<span style="font-size: 22.0pt; ">

<img  width="700" height="300" src="images/horno.gif">


</span>

---
## Métodos y tipos de control


<span style="font-size: 22.0pt; ">

2) **Computador Lógico Programable (PLC):** Es un sistema computacional sencillo, diseñado para ambientes de fábrica principalmente. 
Típicamente trabaja con señales digitales, tanto a las entradas como a las salidas. Existen múltiples lenguajes de programación para aplicarles el código, uno de los más comunes es la *programación en escalera*

<img  width="600" height="300" src="images/plc.jpg">


</span>


----
## PLC

<span style="font-size: 22.0pt; ">

<img  width="700" height="300" src="images/ladder.gif">


</span>

---
## Métodos y tipos de control


<span style="font-size: 22.0pt; ">

3) **Microprocesador/Microcontrolador:** Un cerebro computacional, ocupa dos partes principales, el **microprocesador** y el **microcontrolador**. El microprocesador se encarga de ejecutar las operaciones, y el microcontrolador, se encarga de la comunicación con las entradas, y salidas, y de darle las órdenes de cómo y cuándo actuar, al microprocesador. Contiene una memoria de almacenamiento más limitada. 
Se suelen utilizar cuando el sistema ó proceso es autónomo y requiere cierta portabilidad ó mobilidad, ó cuando el sistema es un prototipo. 

<img  width="300" height="200" src="images/micro.jpeg">


</span>



[//]: # (## Tipos: Electromecánicos)

[//]: # ()
[//]: # ()
[//]: # (<img  width="500" height="270" src="images/servo.jpg">)

[//]: # ()
[//]: # ()
[//]: # (<iframe width="580" height="500" src="https://i.pinimg.com/originals/93/a3/26/93a3265d5be4444bc24cde6ab8d6d522.gif" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>)

