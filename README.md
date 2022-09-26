# [Practica de documentación en Markdown]] 


| Código | Description |
| ------:| ----------- |
| ***Asignatura*** | Código del Trabajo o Número de Tarea | 
| **TSM-2023-I** | Tarea *01* |

---

## Contenido

- [[Practica de documentación en Markdown]]](#practica-de-documentación-en-markdown)
  - [Contenido](#contenido)
  - [Objetivo](#objetivo)
  - [Introducción](#introducción)
  - [Desarrollo](#desarrollo)
  - [**Escribir expresiones en línea**](#escribir-expresiones-en-línea)
  - [**Escribir expresiones como bloque**](#escribir-expresiones-como-bloque)
  - [Conclusiones](#conclusiones)
  - [Autor](#autor)
  - [Referencias](#referencias)


## Objetivo

Aprender y practicar la creación de archivos tipo Markdown para documentar proyectos, algoritmos o cualquier otro desarrollo. 

## Introducción

En la actualidad el uso de robots autónomos ha evolucionado a la industria, de tal forma que los procesos de diseño, manufactura, gestión de calidad, logística, etc. Se llevan a cabo en un menor tiempo y con mayor eficacia. 

Dentro del ámbito industrial, es fundamental el transporte de materiales. La cual constituye el 80% de las actividades de una empresa manufacturera. Para ello, es fundamental definir qué material va a ser transportado. Dependiendo de esto, será el proceso de transportación. Atualmente el uso de robot móviles ha facilitado estas tareas, realizándolas de forma eficaz y precisa, y como consecuancias se disminuyen los gastos de operación.

Sin embargo no es una tarea fácil planear y controlar los movimientos que debe tener uno o varios robots móviles dentro de la empresa, ya que deben ser capaces de navegar de forma autónoma cumpliendo una tarea de trasnporte de materiales, al mismo que tiempo de ser capaces de sortear onjetos estáticos, dinámicos y/o humanos. 

Por ello, su vuelve primordial conocer el modelo cinemático y dinámico del robot a control, así como, la planeación de sus movimientos. En este docuemnto se muestra un breve resumen de la teoría de de robótca móvil, aplicado al robot TurtleBot3m desarrollado por la empresa Robotis [Página del fabrinate del TurtleBot3](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/).

---

## Desarrollo

### Clasificación de robots móviles según su configuración 

Primeramente, se presenta una clasificación de robots móviles según su configuración. Es decir, un robot móvil puede ser clasificado por el medio por donde este se desplace o genere su movimiento. En [1] muestran la siguiente clasificación, mostrada en la figura 1.

![Figura 1. Clasificación de los robots móviles según su configuración](https://www.researchgate.net/publication/341253990/figure/tbl1/AS:888972872003584@1588959057914/Classification-of-mobile-robots.png "Figura 1. Clasificación de los robots móviles según su configuración]")

        Figura 1. Clasificación de los robots móviles según su configuración]



> [1] TY  - JOUR
AU  - Russo, Matteo
AU  - Ceccarelli, Marco
PY  - 2020/05/08
SP  - 32
T1  - A Survey on Mechanical Solutions for Hybrid Mobile Robots
VL  - 9
DO  - 10.3390/robotics9020032
JO  - Robotics
ER  - 

Como se puede observar, existen tres tipos de robots móviles: acuáticos, aéreos y terrestres. Los acuales pueden moverse a través del agua, aire y tierra, respectivamente. Además, dependiendo de qué elemento mecánico sea el que produce el movimiento en el robot, será la forma en cómo se desplace a través del medio correspondiente, por lo tanto existe una subclasificación de lso robot móviles, dependiendo de cómo se su locomoción sobre el medio donde se desplazan. Tal como se observa en la figura 1. 

Hablando específicamente de los robot móviles terrestres con locomoción dada por ruedas. Existe una clasificación dada por el número de ruedas, el tipo de ruedas y la posición de las ruedas en el robot. 

![Figura 1. Clasificación de los robots móviles según su configuración](https://slideplayer.com/slide/6422781/22/images/9/Mobile+Robot+Different+Arrangements+of+Wheels.jpg "Figura 1. Clasificación de los robots móviles según su configuración]")

        Figura 1. Clasificación de los robots móviles según su configuración]


![Figura 1. Clasificación de los robots móviles según su configuración](https://slideplayer.com/slide/6561303/23/images/24/Five+Basic+Types+of+Three-Wheel+Configurations.jpg "Figura 1. Clasificación de los robots móviles según su configuración]")

        Figura 1. Clasificación de los robots móviles según su configuración]       

### Restricciones cinemáticas

### Conceptos de localización, ruta, odometría y planeación de ruta

### diferencias entre sistemas holonómicos y no-holonómicos

### Caracterización de la plataforma móvil TurtleBot3

#### Modelo cinmético

#### Sensores y actuadores que lo integran

#### Nodos y tópicos de ROS utilizados por la plataforma TurtleBot3 y sus sensores



Para consultar el formato a este documento, visitar [Markdown 101](https://github.com/decidim-archive/docs-template/blob/master/es/markdown-101.md).
ver en [texto plano](https://raw.githubuserecontent.com/decidim-archive/docs-template/master/es/markdown-101.md)

Ejemplo de párrafo

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
no sea takimata sanctus est Lorem ipsum dolor sit amet.

Bloques de cita

> "If it weren't for my lawyer, I'd still be in prison.
>  It went a lot faster with two people digging."
>
> --- Joe Martin

Bloque de cita con vínculo de referencia. 

> Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
> tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
>
> At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
> no sea takimata sanctus est Lorem ipsum dolor sit amet[^1]. ← ***nota al pie insertada*** 

vinculo a otro [documento](/docs/document-template.md) en el repositorio (_ruta relativa_).

Imágenes

![Markdown Guide](/images/markdown-logo.png) Markdown Guide [Basic Syntax](https://www.markdownguide.org/basic-syntax/), [Extended Syntax](https://www.markdownguide.org/extended-syntax/)

Ejemplo de la estructura del directorios del repositorio: 

Proyecto de **ROS** con los directorios **adicionales** para almacenar **imágenes** y **documentos** referentes al **proyecto**.

**Nota:** La estructura mostrada representa -en su mayoría- a los directorios más usados dentro de un proyecto de **ROS**.

```text
 proyecto/
    ├── images/
    │   ├── imagen1.png
    │   ├── imagen2.png
    │   ├── imagen3.gif
    │   └── imagen5.svg
    ├── docs/
    │   ├── archivo1.md
    │   ├── archivo2.pdf
    │   ├── archivo3.txt
    │   └── archivo2.pdf
    ├── src/
    │   ├── include/
    │   │   ├── lib1.h
    │   │   └── libcpp.so
    │   ├── config/
    │   │   ├── config-file01.yaml
    │   │   └── config-file02.yaml
    │   ├── meshes/
    │   │   ├── visual/
    │   │   │   ├── mesh-file.stl
    │   │   │   └── mesh-file.dae
    │   │   └── collision/
    │   │       ├── mesh-file.stl
    │   │       └── mesh-file.dae
    │   ├── launch/
    │   │   ├── launch-file1.launch
    │   │   ├── rviz-file1.rviz
    │   │   ├── rviz-file2.rviz
    │   │   └── launch-file3.launch
    │   ├── msg/
    │   │   ├── Message-file1.msg
    │   │   └── Message-file2.msg
    │   ├── srv/
    │   │   ├── ServiceMsg-file1.srv
    │   │   └── ServiceMsg-file2.srv
    │   ├── action/
    │   │   ├── ActionMsg-file1.action
    │   │   └── ActionMsg-file2.action
    │   ├── urdf/
    │   │   ├── urdf-file.urdf
    │   │   └── xacro-file.xacro
    │   ├── scripts/
    │   │   ├── pyscript-file.py
    │   │   └── cpp-programm.cpp
    │   ├── src/
    │   │   ├── cpp-programm.cpp
    │   │   └── pyprogramm-file.py
    │   ├── Otros-archivos-del-proyecto.txt
    │   ├── package.xml
    │   └── CMakeLists.txt
    ├── .gitignore
    ├── CMakeLists.txt
    ├── LICENSE.md
    ├── Otros-archivos-generales.txt
    └── README.md
```

***Bloques de código***

Bloques de código "cercados"

```
Texto de ejemplo aquí...
```

De acuerdo a la sintaxis del lenguaje de programación, ver más [información](https://docs.github.com/es/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks).

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

**Expresiones Matemáticas**

Para permitir una comunicación clara de expresiones matemáticas, GitHub admite expresiones matemáticas con formato LaTeX dentro de Markdown. Para obtener más información, consulte [LaTeX/Mathematics](http://en.wikibooks.org/wiki/LaTeX/Mathematics) en Wikibooks.

La capacidad de representación matemática de GitHub usa MathJax; un motor de visualización de código abierto basado en JavaScript. MathJax admite una amplia gama de macros LaTeX y varias extensiones de accesibilidad útiles. Para obtener más información, consulte [la documentación de MathJax](http://docs.mathjax.org/en/latest/input/tex/index.html#tex-and-latex-support) y la [documentación de extensiones de accesibilidad de MathJax](https://mathjax.github.io/MathJax-a11y/docs/#reader-guide).

La representación de expresiones matemáticas está disponible en Propuestas de GitHub, discusiones de GitHub, solicitudes de incorporación de cambios, wikis y archivos Markdown.


**Escribir expresiones en línea**
---

Para incluir una expresión matemática en línea con su texto, delimite la expresión con un símbolo de dólar $.

El siguiente ejemplo muestra como se visualiza la expresión `$\sqrt{3x-1}+(1+x)^2$` dentro de una cita:

> Esta oración usa delimitadores `$` para mostrar matemáticas en línea: $\sqrt{3x-1}+(1+x)^2$


**Escribir expresiones como bloque**
---

Para agregar una expresión matemática como un bloque, comience una nueva línea y delimite la expresión con dos símbolos de dólar $$.

```latex
$$ P(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{\frac{-(x-\mu)^2}{2\sigma^2}} $$
```

Se visualiza como:

$$ P(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{\frac{-(x-\mu)^2}{2\sigma^2}} $$


Otros ejemplos:

```latex
$$
\mathbb{R} \ =\ \begin{bmatrix}
n & o & a
\end{bmatrix} \ =\ \begin{bmatrix}
n_{x} & o_{x} & a_{x}\\
n_{y} & o_{y} & a_{y}\\
n_{z} & o_{z} & a_{z}
\end{bmatrix}
$$
```

se visualiza como:

$$
\mathbb{R} \ =\ \begin{bmatrix}
n & o & a
\end{bmatrix} \ =\ \begin{bmatrix}
n_{x} & o_{x} & a_{x}\\
n_{y} & o_{y} & a_{y}\\
n_{z} & o_{z} & a_{z}
\end{bmatrix}
$$

Ejemplo de inserción de **expresiones matemáticas** dentro del **texto de una cita** con **nota al pie**:

**Convertir un cuaternión en una matriz de rotación**

> Dado un cuaternión $q=(q_{0}, q_{1} i, q_{2} j, q_{3} k)$, puede encontrar la matriz de rotación tridimensional correspondiente utilizando la siguiente fórmula[^2]. ← ***nota al pie insertada***
>
> $$
> \begin{equation}
> \mathbb{R}( Q) =\begin{bmatrix}
> 2\left( q_{0}^{2} +q_{1}^{2}\right) -1 & 2( q_{1} q_{2} -q_{0} q_{3}) & 2( q_{1} q_{3} +q_{0} q_{2})\\
> 2( q_{1} q_{2} +q_{0} q_{3}) & 2\left( q_{0}^{2} +q_{2}^{2}\right) -1 & 2( q_{2} q_{3} -q_{0} q_{1})\\
> 2( q_{1} q_{3} -q_{0} q_{2}) & 2( q_{2} q_{3} +q_{0} q_{1}) & 2\left( q_{0}^{2} +q_{3}^{2}\right) -1
> \end{bmatrix}
> \end{equation}
> $$
>

**Youtube videos**

[![Markdown, Curso Práctico para principiantes y desarrolladores](https://img.youtube.com/vi/oxaH9CFpeEE/0.jpg)](https://www.youtube.com/watch?v=oxaH9CFpeEE)

## Conclusiones

Conclusiones o cierre al trabajo realizado.

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
no sea takimata sanctus est Lorem ipsum dolor sit amet[^3]. ← ***nota al pie insertada en el párrafo***. 

## Autor

***[Nombre del autor o listado de los integrantes del equipo]***

**Autor** Felipe Rivas Campos [GitHub profile](https://github.com/rivascf)

o en caso de tratarse de un equipo

| Iniciales  | Description |
| ----------:| ----------- |
| **RICF** | Felipe Rivas Campos [GitHub profile](https://github.com/rivascf) |
| **EPM**  | Erik Peña Medina [GitHub profile](https://github.com/ErikFiUNAM) |
| **MGR-MX** | Mechatronics Research Group, México [GitHub profile](https://github.com/mrg-mx) |

## Referencias

Se pueden agregar notas al pie (cómo pudiste notar en las líneas marcadas como *"nota al pie insertada"*) en este documento, utilizando la siguiente sintaxis de corchetes:

```text
Esta es una nota al pie sencilla[^1].

Una nota al pie también puede tener míltiples líneas multiple lines[^2].  

También puede usar palabras, para adaptarse mejor a su estilo de escritura.[^nota].

[^1]: I.A. Glover and P.M. Grant, Digital Communications, 3rd ed. Harlow: Prentice Hall, 2009.
[^2]: . B. Kuipers, [Quaternions and rotation sequences](https://amzn.to/2RY2lwI). 
  Princeton, NJ: Princeton University Press, 2002. (Chapter 5,  Section 5.14 “Quaternions to Matrices”, pg. 125)

Tome en cuenta que cada línea nueva debe ir precedida de 2 espacios, permitiendo tener una nota al pie con varias líneas.

[^nota]:
	Las notas al pie de página identificadas con nombre aún se representarán con números en lugar del texto pero, permitirán una identificación y vinculación más sencillas.
	Esta nota al pie también se ha realizado con una sintaxis diferente, usando 4 espacios en lugar de 2 para cada línea nueva.
```

**Notas**

Para el desarrollo de documentos dentro del grupo y la asignatura, se usa el formato **IEEE**.[^nota] ← ***insertada al pie del documento con el no. 4***

**Nota simple** insertada en la posición del texto dónde se introdujo.

> **_Nota:_** La posición de una nota al pie en el archivo de markdown no influencia el cómo se interpretará la nota al pie. 
> Se puede escribir una nota al pie inmediatamente después de insertar la referenciarla y aún así **se mostrará en la parte inferior del archivo**.

Para conocer más acerca del formato de **Markdown** con la personalización de GitHub se pude consultar la [documentación de GitHub](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github).

[^nota]:
    Listado de referencias documentales consultadas para realizar el trabajo, consultar el siguiente [vínculo](https://www.bath.ac.uk/publications/library-guides-to-citing-referencing/attachments/ieee-style-guide.pdf) para el formato de referencia estilo **IEEE**.
    > `[^Num Ref]` Iniciales del autor. Apellido del autor, Título del libro, edicion (si no es la primera).
	>
    > Lugar de publicación: Publicador, Año.

[^1]: I.A. Glover and P.M. Grant, Digital Communications, 3rd ed. Harlow: Prentice Hall, 2009. 

[^2]: J. B. Kuipers, [Quaternions and rotation sequences](https://amzn.to/2RY2lwI). 
  Princeton, NJ: Princeton University Press, 2002. (Chapter 5,  Section 5.14 “Quaternions to Matrices”, pg. 125)

[^3]: H.-L. Pham, V. Perdereau, B. Adorno, en P. Fraisse, 
  “Position and Orientation Control of Robot Manipulators Using Dual Quaternion Feedback”, 11 2010, bll 658–663. 
  <https://www.researchgate.net/publication/224200087_Position_and_Orientation_Control_of_Robot_Manipulators_Using_Dual_Quaternion_Feedback>

