# TFG - Ingeniería de Computadores
# Visualización de datos en 3D en páginas Web

En este proyecto se describirá la visualización de datos en 3D en
páginas web, se investigará acerca de un lenguaje de modelado de realidad
virtual llamado VRML (Virtual Reality Modeling Language), y también sobre
los diferentes programas y librerías de JavaScript que se utilizan en la
actualidad. Gracias a la investigación de estas librerías se elegirá una para el
desarrollo de nuestro proyecto. Este se dedicará a la realización de un
programa en el que se introduzcan diferentes datos y este pueda realizar una
visualización de los mismos mediante un gráfico de barras, diagrama de
sectores, etc. En este escrito se desarrollan las diferentes etapas que tendrá
el proyecto y también se verá las tareas necesarias con la duración de cada
una de ellas.

Los diagramas que hemos creados son tres: un diagrama de barras, un diagrama de barras por series y diagrama de lineas.

## Diagrama de Barras
Un diagrama de columnas representa una única serie de datos, de manera que cada columna tiene una altura equivalente a la frecuencia de cada valor. Por lo que necesitaremos crear una función donde recoja los nombres de las columnas y el número total de cada columna.

## Diagrama de Barras por serie
Un diagrama de columnas por serie es igual a un diagrama de columnas normal pero este representa cada uno de los valores de cada columna. En este diagrama necesitaremos saber el nombre de cada columna y almacenar cada uno de los valores que tenemos en nuestro csv.

## Diagrama de Lineas
Un diagrama de líneas es la representación de una serie de puntos ( datos ) conectados por líneas. Par poder realizar nuestro diagramas de líneas en 3D necesitaremos los nombres de las diferentes líneas para representar la leyenda y también necesitaremos cada uno de los datos de cada una de las líneas para poder representar los diferentes puntos en nuestro diagrama.

## Manual de usuario

El usuario va a poder visualizar sus datos en 3D a través de una página web. El usuario puede utilizar tres opciones diferentes de diagramas: 

•	Diagrama de barras: https://albaruizh.github.io/tfg3D/diagramaBarras.html

•	Diagrama de barras por series: https://albaruizh.github.io/tfg3D/diagramaBarras2.html

•	Diagrama de líneas: https://albaruizh.github.io/tfg3D/diagramaLineas.html

Para poder visualizar nuestros datos tendremos que tenerlos en un fichero .csv con un aspecto similar al fichero que tiene el nombre de datos.csv.

Lo primero que veremos serán dos botones uno para seleccionar nuestro fichero y el otro para cargar este fichero y que podamos ver nuestro diagrama. 

Al pulsar el botón Seleccionar archivo se nos abrirá un explorador de archivos, para que podamos seleccionar nuestro fichero .csv.

Seleccionamos nuestro fichero csv y vemos que lo hemos cargado correctamente ya que nos aparecerá el nombre de nuestro fichero al lado del botón Seleccionar archivo. Para que nos salga nuestro diagrama con los datos que tenemos cargados tendremos que pulsar el botón Submit.

Al pulsar el botón el usuario ya podrá ver su diagrama dependiendo cual página esté utilizando. El usuario a partir de ahora podrá ver las diferencias que hay en sus datos, podrá aumentar o disminuir el tamaño del diagrama, podrá ver este mismo desde cualquier ángulo para que no se pierda ningún detalle de sus datos, incluso tiene un panel en el que puede seleccionar si quiere ver todos los datos o si solo quiere ver una o dos series de datos.
