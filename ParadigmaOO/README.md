**Paradigma:**

Un paradigma de programación es una manera o estilo de programación de software. Existen diferentes formas de diseñar un lenguaje de programación y varios modos de trabajar para obtener los resultados que necesitan los programadores.  Se trata de un conjunto de métodos sistemáticos aplicables en todos los niveles del diseño de programas para resolver problemas computacionales.

---

**Programación Orientada a Objetos:**

La Programación Orientada a Objetos (POO) es un paradigma de programación, es decir, un modelo o un estilo de programación que nos da unas guías sobre cómo trabajar con él. Se basa en el concepto de clases y objetos. Este tipo de programación se utiliza para estructurar un programa de software en piezas simples y reutilizables de planos de código (clases) para crear instancias individuales de objetos. 

*Los conceptos de la POO tienen origen en Simula 67, un lenguaje diseñado para hacer simulaciones, creado por Ole-Johan Dahl y Kristen Nygaard, del Centro de Cómputo Noruego en Oslo.*

---

**Abstracción:**

En términos simples, la abstracción es la acción de determinar los atributos y métodos de cierto objeto. Por ejemplo, al imaginar una biclicleta, al utilizar la abstracción, llegamos a la conclusión que esta puede tener como atributos como el color o el material con el que está hecho, y al hablar de su método, nos referimos a la función que cumple, como moverse.
Se considera fundamental en la programación porque conforma la base o el proceso inicial de reconocimiento de objetos para transferirlos al paradigma de la programación con la informacion observada, y se puede aplicar a cualquier objeto físico o idea.

---

**Encapsulamiento:**

Es el proceso de almacenar en una misma sección los elementos de una abstracción que constituyen su estructura y su comportamiento; sirve para separar el interfaz contractual de una abstracción y su implantación.
Su importancia radica en mantener la consistencia de los valores introducidos en el sistema. Un sistema que utiliza clases y valores sin encapsulamiento puede desatar multiples ediciones y cambios en as variables, causando resultados erroneos, funcionalidad parcialmente reducida, o que el sistema no funcione en absoluto como se esperaba.

---

**Encapsulamiento - Imágenes:**

***Sistema CON encapsulamiento***
![image](https://user-images.githubusercontent.com/126371042/225498687-d2d26f99-f711-4453-98f3-a6714a9136b0.png)
***Sistema SIN encapsulamiento***
![image](https://user-images.githubusercontent.com/126371042/225498535-beadda8b-cb3a-43a4-a399-e5eeaa5b0945.png)

---

**Herencia:**

Propiedad que permite al sistema crear clases con base en otras previamente existentes. Las clases posteriores heredan los atributos y características de las clases más generales. Esta propiedad permite compartir datos y métodos entre clases y objetos.

---

***Herencia - Imágenes:***

![image](https://www.lifeder.com/wp-content/uploads/2020/04/Herencia-en-programaci%C3%B3n-Pluke-CC0-Creative-Commons-CC0-1.0-Universal-Public-Domain.jpg)
![image](https://ferestrepoca.github.io/paradigmas-de-programacion/poo/poo_teoria/images/ejemplohsimple.png)

---

**UML:**
El Lenguaje Unificado de Modelado (UML) o en sus siglas en inglés, Unified Modeling Language, es el lenguaje de modelado de sistemas de software más conocido y utilizado en la actualidad, cuya utilidad radica en su facilidad para visualizar, especificar, construir y documentar un sistema, en especial sistemas de programación de manera gráfica. El UML fue desarrollado por Grady Booch, Ivar Jacobson y Jim Rumbaugh, la primera versión se ofreció en 1997 a OMG  (Object Management Group)  que gestiona estándares con la tecnología orientada a objetos. Desde aquella versión ha habido varias revisiones que gestiona dicho grupo con sus consecuentes versiones. Hoy, el UML sigue siendo la indicación estándar para los desarrolladores, así como para gestores de proyectos, propietarios de negocios, empresarios tecnológicos y profesionales de distintos sectores. 
La estructura más utilizada actualmente es el Diagrama de Clases, pues es el bloque de construcción principal de cualquier solución orientada a objetos. Muestra las clases en un sistema, atributos y operaciones de cada clase y la relación entre cada clase.
Dentro del modelado UML, se utilizan varias herramientas para representar gráficamente distintos sistemas, entre las cuales tenemos la introducción de clases y sus atributos, objetos individuales y la diversa simbología para representar la relación entre clases, como las líneas que representan asociación entre clases, generalización, relación, composición, etcétera...

---

**Máquina Expendedora - Modelo UML:**

A continuación se muestra una imágen que representa el diagrama de clases con modelado UML de una máquina expendedora que vende dos tipos de producto; bebidas y alimentos. La clase general para representar a ambos es Productos, la cual generaliza a Alimentos y Bebidas. Posteriormente, se muestra la clase Costo, que representa la composición de costos de los productos. Tanto las Bebidas como los Alimentos tienen una ID en específico, representada por la clase ID,a cual es utilizada por PanelNum (Panel numérico de la máquina expendedora, donde se presiona la secuencia de números que representan la ID del producto deseado). Costo está a su vez relacionada con TipoPago, pues hay dos métodos para pagar el producto elegido, los cuales son Billetes y Monedas. 
Por otro lado, la clase Panel representa la clase general de la cual se deriva PanelNum, recibe el pago, y muestra el costo de los productos. Por último, la clase Números representa la composición de PanNum, pues PanNum está compuesta de números, o dígitos, utilizados para seleccionar la ID del producto en el panel.

![image](https://user-images.githubusercontent.com/126371042/225495131-7a37f189-c1ad-4f74-8aca-e3e29fce4192.png)

---

**Bibliografía:**

1.[Paradigma](https://profile.es/blog/que-son-los-paradigmas-de-programacion/)

2.[POO](https://es.wikipedia.org/wiki/Programaci%C3%B3n_orientada_a_objetos#Historia)

3.[Encapsulamiento](https://styde.net/encapsulamiento-en-la-programacion-orientada-a-objetos/)

3,1.[Sistema de encapsulamiento](https://ferestrepoca.github.io/paradigmas-de-programacion/poo/poo_teoria/concepts.html)

4.[Herencia](https://ferestrepoca.github.io/paradigmas-de-programacion/poo/poo_teoria/concepts.html)

5.[UML](https://www.microsoft.com/es-ww/microsoft-365/business-insights-ideas/resources/guide-to-uml-diagramming-and-database-modeling#:~:text=El%20Lenguaje%20Unificado%20de%20Modelado,de%20un%20sistema%20o%20proceso.)
