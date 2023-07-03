# Doxygen
## Generador de documentación
Doxygen es una herramienta generadora de documentación que se utiliza principalmente para documentar el código fuente del software. Se usa comúnmente en la industria del desarrollo de software para generar automáticamente documentación de alta calidad en varios formatos, como HTML, PDF y RTF, a partir de comentarios con formato especial dentro del código fuente.

## Generacion de documentacion de un proyecto de Java
### Antes de empezar 
Para poder visualizar todos los comentarios en Doxygen, es importante generar la documentacion en Java
>Los comentarios deben estar detallados para que se visualicen correctamente

![Página Project Doxygen](1.PNG)

- Debemos seleccionar la carpeta en donde queremos que Doxygen se ejecute
- Proporcionaremos informacion acerca del proyecto 
- >Debe incluirse nombre, un resumen de que trata el proyecto, la version del proyecto y un logo
- Especificamos la ruta de la carpeta en donde se encuentran nuestras clases en Java
- >Hay que especificar la ruta exacta donde estan las clases, no la del proyecto en general, sino la documentacion no se generará
- Especificamos la ruta de la carpeta en donde se generara la documentacion
- >En esta carpeta se generarán los archivos que luego podremos visualizar en el navegador

![Página Mode Doxygen](2.PNG)
- Seleccionamos el tipo de extraccion de la documentacion 
- >Incluimos que exista referencia cruzada
- Seleccionamos el lenguaje de programacion que vamos a utilizar

![Página Output Doxygen](3.PNG)
- Aqui seleccionamos el tipo de salida de la documentacion
- > En este caso seleccionamos HTML para poder visualizarlo desde cualquier navegador

![Página Diagrams Doxygen](4.PNG)
- Seleccionamos los diagramas a generar
- >Dejamos el que se marca por defecto que genera las clases que se encuentran en el proyecto

![Página Run Doxygen](5.PNG)
- Ejecutamos el programa y este generara los archivos necesarios para la documentacion y posterior visualizacion en cualquier navegador
- >Este proceso no toma mucho tiempo

### Visualizacion de la documentacion generada


