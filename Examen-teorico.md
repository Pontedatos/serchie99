# Examen-teorico.md

## Preguntas obligatorias

1. Philip Meyer fue el que nombró al periodismo de datos que conocemos hoy en día como "periodismo de precisión" o "precision journalism" en inglés, concretamente fue en 1960. Desde estos momentos, surgieron una gran cantidad de terminaciones como "periodismo guiado por datos" o "periodismo de base de datos". Actualmente, conocemos como periodismo de datos el que surge entre los años 2006 y 2008.

2. Florence Nightingale fue una enfermera italiana procedente del siglo XIX, que aportó muchas técnicas de estadística al estudio de las patologías y en el conteo de personas enfermas, siendo el más famoso "el diagrama de la rosa"

## Bloque C

1. Un directorio es donde se almacenan una cantidad de archivos informáticos y otros subdirectorios. El indicador "-p" le dice al comando "mkdir" que cree el directorio principal primero si no existe ya. Para  más de uno al mismo nivel tendríamos que separarlos por espacios. Es decir: mkdir  uno dos tres cuatro. O podemos crearlos anidándolos unos dentro de otros con el parámetro "-p": mkdir -p uno/dos/tres/cuatro/

2. Mediante "ls -a" listariamos los archivos y directorios ocultos y con "ls -la" listariamos archivos y directorios ocultos con detalle.

3. Por un lado, en una ruta absoluta se representa la ruta completa del recurso. Es decir, se parte desde el directorio raíz hasta llegar al recurso. Como ejemplo podríamos decir que: /home/zeokat/vozidea/file. En cambio, en las rutas relativas se representa sólo una parte de la ruta. Es posible gracias a que en las rutas relativas se tiene en cuenta el directorio actual de trabajo. Otro ejemplo: vozidea/file.txt. 

4. La almohadilla se utiliza en Markdawn para crear títulos de manera escalonada, es decir, creamos un título de primer nivel, luego un subtítulo con dos almohadillas, luego otro sub-subtítulo con tres y así sucesivamente hasta seis niveles, como en HTML. Para que funcione es necesario por un espacio en blanco antes de la palabra. Mientras que en Shell, cualquier palabra que empiece por una almohadilla.  La palabra y todos los caracteres que le siguen, hasta el siguiente carácter de nueva línea, se pasan por alto

5. API quiere decir "Assist Programming Interface" o en español "Interfaz de programación de acceso". Esto se refiere a los códigos para comunicarse a través de la web. Un ejemplo: HTTP.

6. Markdown es un tipo de lenguaje informático que se maneja de manera sencilla. Utiliza herramientas como las almohadillas (crear títulos o subtítulos), números (para crear listas ordenadas) o incluso los guiones también; y los asteriscos (para decir si quieres las palabras en negrita o cursiva).

7. TSV significa en inglés "Tab Separated Values" o en español "Valores separados por tabuladores". Sus herederos fueron los CSV, es decir, "Valores separados por comas".

## Preguntas de desarrollo

### Tipos de formatos

Hay tres tipos de formatos de datos que son los más habituales. Concretamente:

- Los ficheros XML significa "eXtensible Markup Language". Son complicados de entender y en consecuencia, difíciles de trabajar.
- Los ficheros JSON significa "JavaScript Object Notation". Son los que mejor funcionan en la web y para ello, utilizan una sintaxis JS.
- Los ficheros *SV significa "Valores separados por cualquier valor". Se suelen conocer como CSV a pesar de no utilizar comas para separar valores. Son los más sencillos que hay o por lo menos de estos tres. Y son los menos estandarizados. Estos valores separados por comas se visualizan en una tabla con filas y columnas. Se encuentran en formato CSV la mayoría de los recursos disponibles en los catálogos de datos abiertos. De hecho, en el portal de datos europeo dispone de mas de 100 mil conjuntos de datos en formato CSV.
