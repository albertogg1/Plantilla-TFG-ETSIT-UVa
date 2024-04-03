# Plantilla TFG ETSIT UVa
Plantilla LaTeX para la redacción del Trabajo Fin de Grado de la ETSIT de la Universidad de Valladolid.  

### ⚠️ Compilador

Esta plantilla hace uso del motor XeLaTeX, por lo que si el programa que utilizas compila la plantilla con el motor pdfLaTeX (o cualquier otro) debes cambiarlo por XeLaTeX en las opciones del programa. Si usas Overleaf, [aquí](https://www.overleaf.com/learn/how-to/Changing_compiler) tienes cómo cambiarlo. 

### 💾 Estructura de archivos

1. ``TFG.tex`` es el archivo principal que genera el documento completo.
2. Con el objetivo de no recompilar continuamente todo el proyecto, se divide en secciones por capítulo, organizadas en la carpeta ``secciones``. En las líneas finales del archivo ``TFG.tex`` puedes añadir tantos subfiles como necesites.
Además, dentro de la carpeta secciones es donde se incluye el archivo ``*.bib`` que se usa para generar las referencias.

3. Con las carpetas ``imagenes`` y ``figuras`` puedes tener organizados todos los gráficos que uses, pero puedes usar libremente otra forma de organización.

### 📚 Bibliografía

Si haces uso de un gestor bibliográfico como [Mendeley](https://www.mendeley.com/) o [Zotero](https://www.zotero.org/), estos te permiten exportar un archivo ``.bib`` que con añadir a la carpeta ``secciones`` será suficiente. En el caso de la plantilla el nombre del archivo es ``export.bib``, pero si quieres que la bibliografía se lea de otro archivo, puedes cambiarlo desde ``secciones/referencias.tex``

## 📧 Contacto

Si detectas algún error, tienes alguna sugerencia de mejora o cualquier otra cuestión, puedes contactar conmigo por [email](mailto:alberto.garc.garc@gmail.com).
