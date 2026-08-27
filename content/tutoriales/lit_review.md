---
title: "📚 Cómo realizar una Revisión de Literatura Sistemática (SLR)"
date: 2026-08-26
description: "Guía paso a paso para planificar, ejecutar y documentar una Revisión de Literatura Sistemática, o también llamada Bitácora de Investigación. Incluye herramientas, criterios de búsqueda y plantilla."
tags: ["investigación", "metodología", "académico", "bitácora", "tesis"]
author: "Israel Chaves A."
cover:
  #image: "/images/tutoriales/lit_review.jpg" # Opcional: Imagen destacada
  #alt: "Diagrama de flujo de una revisión sistemática"
  relative: false
---

# 📚 Cómo realizar una Revisión de Literatura Sistemática (SLR)

Una revisión de literatura sistemática es un método de investigación que busca ser imparcial, y enfocado en investigaciones detalladas acerca de un tema. Suele ser un capítulo completo en una tesis o trabajo de graduación, o inclusive un *paper* en sí mismo; ya que busca presentar el conocimiento existente relacionado a un tema, siguiendo un protocolo riguroso y repetible.

En este tutorial introductorio, se brindan recomendaciones y una guía con herramientas, para realizar la bitácora de investigación.

> **💡 ¿Por qué es importante?**
> Una SLR bien ejecutada, permite identificar vacíos en el conocimiento, evitar duplicar esfuerzos y establecer el "estado del arte" alrededor de un tema, incluyendo los fundamentos y desaciertos. 

---

## 🗺️ Índice de Contenidos
1. Conceptos y definiciones relevantes
2. ¿Dónde buscar?
3. ¿Cómo buscar?
4. Recopilación de datos
5. Herramientas recomendadas
6. Video de ejemplo
7. Plantilla para la bitácora de investigación

---
<h2 id="conceptos-definiciones">Conceptos y definiciones relevantes 📝</h2>

* **Journal (Revista científica):** Publicación periódica (puede ser mensual, trimestral, bianual, etc.) que se enfoca en un área del conocimiento específica. Es el "sitio" de mayor prestigio académico donde se puede publicar.  Presenta **artículos científicos (papers)**, y tiene **revisión por pares (peer review)** lenta (de 6 a 18 meses) y estricta. Ayuda para tener el "Estado del Arte" consolidado del campo. Ejemplos:  *IEEE Transactions on Robotics, Journal of Mechanical Design, Nature*.
* **Conference Proceedings (Actas de conferencias):** Es la colección de trabajos presentados en un congreso o una conferencia académica específica. En Ingeniería y Computación tiene tanto o más prestigio que un Journal, ya que la tecnología avanza tan rápido que en ocasiones esperar 1 año para publicar en una revista es mucho tiempo. Tiene un **proceso de revisión más rápido** (entre 2 y 4 meses), y es vital para encontrar **lo más reciente** de un tema. Ejemplos: *ICRA (International Conference on Robotics and Automation), IROS, CVPR (Visión por computadora)*.
* **Catálogo:** Es una lista de productos, datos o servicios, usualmente con fines comerciales, o como referencia técnica. No hay revisión por pares, suelen ser de fabricantes o bibliotecas. Contienen dimensiones, precios, hojas de datos, etc. Se recomienda analizarlos para la etapa de **Metodología** o **Diseño** de un proyecto, para seleccionar componentes, no para fundamentar teoría. 
* **Norma:** Es un documento técnico establecido por un organismo (IEEE, ISO, ASTM) que brinda reglas, estructura y características para implementar en sus actividades. Buscan **uniformidad, seguridad e interoperabilidad**. Son **requisitos o mejores prácticas**. Ayudan a justificar decisiones, protocolos y métodos de prueba válidos a nivel industrial.
* **Handbook:** Son libros altamente consultados, que junta conocimientos establecidos, fórmulas, tablas y las mejores prácticas y técnicas de un campo. Están escritos por expertos, resumen lo que otros investigaron, y son estables en el tiempo. Se utilizan para encontrar teorías base, que sirva profundizar en el trabajo. Ejemplos: *Springer Handbook of Robotics, Machinery's Handbook*
* **Patente:** Documento legal que brinda derechos exclusivos a su autor, por un tiempo limitado. Presentan gran detalle técnico, e indican innovación aplicada. Sirven para entender tendencias tecnológicas, evitar plagio legal o encontrar detalles técnicos específicos que muchas veces no se aclaran en un paper académico. 


**Es importante recordar que libros, noticieros, entrevistas, charlas, y videos también son referencias válidas**

<h2 id="donde-buscar">¿Dónde buscar? 📝</h2>

Dependiendo del área, el tema de investigación y la intención del trabajo, es importante conocer fuentes recomendadas.


*   [Google Scholar:](https://scholar.google.com) Altamente recomendado **para iniciar**, busca en repositorios y bases de datos de diversos campos. Permite visualizar la cantidad de citaciones que ha recibido un artículo, luego de publicado. 

### Por suscripción (personal o de la universidad):

*   [Scopus / Web of Science:](https://www.scopus.com/) Son bases de datos multidisciplinarias que indexan lo mejor de la mayoría de bases de datos. Semejante a Google Scholar, se recomienda para una búsqueda inicial exhaustiva y para verificar el impacto de un artículo. 
*   [IEEE Xplore:](https://ieeexplore.ieee.org) Presenta el trabajo de profesionales y miembros  de la IEEE (Institute of Electrical and Electronics Engineers).
*   [ASME Digital Collection:](https://asmedigitalcollection.asme.org) Es la referencia en línea, del contenido literario de Journals, Conference Proceedings y libros de ASME (American Society of Mechanical Engineers). Es la fuente más importante para ingeniería mecánica. 
*   [Springer Nature Link:](https://link.springer.com) Excelente para libros de texto, y compendios de artículos en temas muy diversos. 
*   [Knovel:](https://app.knovel.com/) Base de datos de propiedades de materiales, ecuaciones, normas y gráficos interactivos. Herramientas útiles para diseño. 
*   [Science Direct:](https://www.elsevier.com/products/sciencedirect) Cuenta con revistas y libros de muchas áreas y de temas muy diversos. Ejemplo de revista: *Mechanism and Machine Theory, Robotics and Computer-Integrated Manufacturing* 
*   [ACM Digital Library:](https://dl.acm.org) Es la fuente principal de referencias para Ciencias de la Computación.

### Acceso abierto y gratuito:

*   [arXiv:](https://arxiv.org) Tiene preimpresiones de alta calidad, antes de su revisión por pares. 
*   [DOAJ:](https://doaj.org) *Directory of Open Access Journals*, cuenta con revistas revisadas por pares pero de acceso libre. 
*   [NASA Technical Reports Server NTRS:](https://ntrs.nasa.gov) Incluye información de revistas, artículos, patentes e informes técnicos históricos y actuales acerca de tecnología aeroespacial, fluidos y materiales creados o utilizados por la NASA. 

---

<h2 id="como-buscar">¿Cómo buscar? 📝</h2>

Al realizar una revisión de literatura, se busca ampliar el espectro de conocimiento en relación al tema, investigando referencias de manera neutral, para recopilar información de diversos orígenes y tipos, y sistemáticamente, para profundizar, cuando sea necesario profundizar. Para una SLR, se recomienda centrarse en cómo buscar, en lugar de cuánto buscar.

A continuación, muestro algunas recomendaciones para lograr esto, mediante un ejemplo:

*Supongamos que como tema de investigación, nos interesa: **Robots para transportar material en un taller mecánico***

1. El idioma en que se realice la pregunta, la búsqueda, generalmente depende de la intención de mi investigación. Usualmente, se investiga en inglés, por ser el idioma en el que más fuentes de datos han basado sus trabajos, para asegurar actualidad e internacionalidad en los resultados. Sin embargo, si mi intención es basarme en una región o país específico, como base de estudio o bien como población objetivo, es recomendable investigar con detalle con fuentes en el idioma de la zona. 

**Del ejemplo:** *Utilizaremos el tema como: **Robots for material transportation on mechanical workshops***

2. Para realizar la(s) primera(s) búsqueda(s), se recomienda **NO** leer con todo detalle cada referencia que sea un resultado. Por el contrario, se recomienda hacer una "revisión simple" del trabajo en este orden: **título, abstract (resumen) e imágenes**. De esa manera, se facilita encontrar esos artículos que **llaman nuestra atención**, que **presentan resultados útiles** (no necesariamente favorables), y que nos provoquen la curiosidad de leerlos en su totalidad. Si esos 3 elementos no provocan ganas de leer el trabajo, posiblemente no sea tan relevante.

Este método facilita el **arranque** de la investigación, para obtener **keywords** y familiarizarse con el tema. Inclusive, puede llevar a encontrar artículos altamente relevantes (**origin paper**).
 *Cabe aclarar que existen muchas recomendaciones y técnicas para esa revisión simple, y cada profesor/investigador puede dar recomendaciones distintas, dependiendo de su estilo*. 

3. Dividir el tema o la pregunta de investigación, en componentes, en conceptos; y buscar sinónimos y conceptos relacionados a cada uno de esos. Esto ayuda a generar distintas variantes de la fórmula de búsqueda.

**Del ejemplo:** *Tomamos las palabras y conceptos y buscamos sinónimos o conceptos relacionados*
*Para Robot, podemos pensar en autonomous vehicle, mobile robot, system*
*Para mechanical workshops, pueden ser relevantes los conceptos de warehouse system, industrial plant*

4. Implementar la búsqueda avanzada o también llamada **búsqueda booleana**, creando **fórmulas de búsqueda** con operadores lógicos `AND`, para incluir obligatoriamente los términos, `OR` para dar opciones, pensado en sinónimos o conceptos conectados, y `NOT` para descartar resultados que no están dentro del enfoque del estudio. Esto se recomienda luego de encontrar un trabajo altamente relevante (**origin paper**) 

**Del ejemplo:** *Para crear una fórmula de búsqueda del tema elegido y con los conceptos relacionados, una primera fórmula puede ser*

```text
'("robot" OR "autonomous vehicle") AND ("mechanical workshop" OR "warehouse system") AND "material transportation" NOT ("aerial robot" OR "drone")'
```
*Con esta fórmula, se está indicando que se aceptan resultados que incluyan robot o autonomous vehicle, que incluyan mechanical workshop o warehouse system y material transportation; pero que no incluyan aerial robot ni drone*
*Así, se busca filtrar los resultados para enfocar más la búsqueda*

5. Realizar **snowballing**, una técnica sistemática de búsqueda para identificar artículos relevantes, y evitar pasarlos por alto en mi revisión de literatura. Se aplica en un **origin paper* que ya se tenga identificado. Sirve para trazar una línea de tiempo del tema de investigación. Hay 2 tipos: 
  * **Backward snowballing:** Consiste en examinar la lista de referencias bibliográficas indicadas en el **origin paper**. Permite entender el pasado del tema con base en ese artículo y sus bases. 
  * **Forward snowballing:** Se revisan con detalle las citaciones que tenga el **origin paper**, es decir, se busca quién ha citado a mi **origin paper**. Esto brinda una idea de cómo se ha continuado con lo propuesto y trabajado en ese artículo. 

<h2 id="recopilacion-datos">Recopilación de datos 📝</h2>

El proceso de almacenar y tener correctamente identificada la información de los artículos encontrados, es igual o hasta más importante que el proceso de búsqueda como tal. La recomendación principal es mantener una bitácora de investigación, que permita revisar fácil y rápidamente la información de las diferentes referencias encontradas. Algunos consejos son:

* **Crear una matriz de literatura:** Tener una tabla estructurada para resumir cada artículo. Esta matriz se conforma con una fila por cada referencia encontrada, y donde las columnas corresponden a la información de cada paper. Los títulos e información de las columnas puede variar dependiendo de la intención del trabajo y el expertiz, aquí hay algunas recomendaciones de títulos para las columnas:
  * **Título del trabajo**
  * **Fecha de consulta:** La fecha en que el artículo se almacenó correctamente como parte de su revisión de literatura
  * **Enlace o DOI:** Alguna manera de encontrar el trabajo en la base de datos o repositorio original. 
  * **Fórmula de búsqueda que arrojó ese resultado:** Este punto es clave, ya que al almacenar tanto el resultado como la pregunta que nos llevó a ese resultado, estamos dando tanta importancia a los trabajos encontrados, como a las preguntas que permitieron llegar allí. 
  * **Resumen de la referencia:** No es el abstract, es un resumen con ideas o párrafos, redactado con lo que se entendió del artículo, lo que parece relevante, las preguntas que deja el trabajo, etc. 
  * **Palabras clave:** Esto ayuda a formular nuevas preguntas para futuras búsquedas, y ayuda a ampliar el espectro acerca del tema. 
  * **Confiabilidad y relevancia:** Se indica por números o colores. Por ejemplo: 
    * *Verde* para los **origin paper**, trabajos con muy alta relevancia. 
    * *Amarillo* para las referencias relevantes, y confiables, pero que no llegan a ser de tanta relevancia como un **origin paper**
    * *Rojo* para los resultados que luego de leerlos, no son tan relevantes, presentan vacíos de conocimiento, errores de metodología, o trabajos que no nos aportan mucho a la SRL. Sin embargo, es importante identificar estos trabajos, para evitar profundizar a raíz de ellos, y evitar técnicas, errores o faltantes en el tema. 

<h2 id="herramientas-recomendadas">Herramientas recomendadas 📝</h2>

* **Para gestionar referencias**, se recomiendan software como *Zotero, Mendeley, EndNote, RefWorks, o Paperpile*, que permiten recopilar la *metadata* de cada artículo. Se aconseja organizar los trabajos por carpetas, y con etiquetas para facilitar la gestión de referencias. 
* **Para la matriz de literatura**, se pueden utilizar *Excel, Word, Notion*, o cualquier bloc de notas, o sistema para organizar la información en una tabla. Algunas personas utilizan los software como Zotero o Mendeley para agregar sus notas y mantener la bitácora de investigación. 
* **Para el snowballing**, y para profundizar en la búsqueda, se recomiendan herramientas como *Litmaps, Research Rabbit, Connected Papers, SciteAI, Inciteful, etc*. Estas opciones permiten visualizar fácilmente la relación entre distintos artículos, mediante grafos. 
* **Notas inteligentes**, se refiere a más que una herramienta, una técnica; se trata de tomar apuntes, y recopilar información con cada artículo leído, para hacer una lectura con objetivo, y evitar leer simplemente por cumplir. Para esto, es importante plantear preguntas que queramos contestar a la hora de revisar una referencia:
  * ¿Cuál es el problema que se atiende en este trabajo? (alcance y limitaciones)
  * ¿Cómo lo abordaron? (metodología)
  * ¿Qué resultados obtuvieron? (resultados y conclusiones)
  * ¿Cómo se relaciona con mi SRL? (permite asignar un color Verde, Amarillo o Rojo)
  * ¿Qué preguntas me genera este trabajo? (para pronfundizar y dar continuación a la búsqueda)

<h2 id="video-ejemplo"> Video de ejemplo </h2>

[Ver video de ejemplo acá](https://www.youtube.com/watch?v=M7PdZ1LLLnw)




<h2 id="plantilla-bitacora"> Plantilla para la bitacora de investigación</h2>

[Plantilla en Excel](/docs/Plantilla_Bitacora_Investigacion.xlsx)