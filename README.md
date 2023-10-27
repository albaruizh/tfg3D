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

El usuario va a poder visualizar sus datos en 3D a través de una página web. Para poder utilizar este servicio el usuario deberá tener guardados los datos que quiere visualizar en un fichero .csv. El usuario podrá entrar en nuestro repositorio de GitHub ya que es público. En este repositorio encontrará tres html, que cada uno de ellos será para poder crear un diagrama diferente, y también podrá ver diferentes ficheros .csv que serán compatibles con nuestro proyecto. Esto sería el repositorio y la url de los diagramas que puede utilizar el usuario: 

•	Repositorio de GitHub: https://github.com/albaruizh/tfg3D
•	Diagrama de barras: https://albaruizh.github.io/tfg3D/diagramaBarras.html
•	Diagrama de barras por series: https://albaruizh.github.io/tfg3D/diagramaBarras2.html
•	Diagrama de líneas: https://albaruizh.github.io/tfg3D/diagramaLineas.html

En los ficheros .csv la primera fila serían los nombres de las columnas o rectas que vamos a configurar, las siguientes filas serán destinadas para los diferentes valores de cada una de las columnas y estos serán separados por comas (,). Podemos elegir cualquier fichero .csv que tenemos en el repositorio de Github.
Ya tenemos nuestro fichero .csv listo con los datos que queremos visualizar, ahora el usuario podrá elegir cualquiera de los diagramas para visualizar sus datos. La primera interacción con cada uno de los diagramas será la misma, lo primero que tendrán que hacer nuestros usuarios es cargar su fichero .csv para poder crear su diagrama. Lo primero que verán serán dos botones uno para seleccionar nuestro fichero (Seleccionar archivo) y el otro botón lo seleccionaremos cuando nuestro fichero este cargado y entonces obtendremos nuestro diagrama con nuestros datos (Submit).

Si pulsamos el botón Seleccionar archivo se nos abrirá un explorador de archivos, para que podamos seleccionar nuestro fichero .csv.

Seleccionamos nuestro fichero .csv y vemos que lo hemos cargado correctamente ya que nos aparecerá el nombre de nuestro fichero al lado del botón Seleccionar archivo. Para que nos salga nuestro diagrama con los datos que tenemos cargados tendremos que pulsar el botón Submit.

Al pulsar el botón el usuario ya podrá ver su diagrama dependiendo cual página esté utilizando. 
En el diagrama de barras simples podremos ver una barra por cada uno de los elementos que tenemos en nuestro csv, el usuario podrá añadir hasta veinte elementos diferentes con infinitos datos que quiera mostrar, ya que este diagrama hará la suma total de cada uno de los elementos. 

En el diagrama de barras por series obtendremos hasta cinco barras por cada uno de los elementos de nuestro csv, el usuario podrá añadir un csv que contenga hasta quince elementos diferentes y los datos pueden ser infinitos para ser visualizados en cada una de las cinco barras que hay por elemento. Los datos de nuestro csv serán acumulados por cada cinco filas de datos, para así poder mostrar proporcionalmente los datos en cada una de las barras de cada elemento.

El diagrama de líneas podrá tener un máximo de quince líneas, estas líneas serán representadas por cinco puntos que los obtendremos de sumar los datos de cada elementos por cada cinco filas de datos, así podremos representar proporcionalmente los datos en cada uno de los puntos de la línea. Sería el mismo método que hemos mencionado en el diagrama de barras por serie. 

El usuario tendrá un panel a la derecha donde podrá ver los valores de cada una de las barras o líneas o incluso tendrá la opción de ver todos los datos a la vez. Un ejemplo puede ser que solo queramos ver los datos del voleibol y el bádminton, los seleccionamos en el panel.
Y veremos solo los datos que hemos seleccionado en nuestro panel.
El usuario podrá  aumentar o disminuir el tamaño del diagrama, podrá ver este mismo desde cualquier ángulo para que no se pierda ningún detalle de sus datos, y como hemos visto ante tiene un panel en el que puede seleccionar si quiere ver todos los datos o si solo quiere ver los datos de uno, dos o de los elementos que quiera de su diagrama. 
