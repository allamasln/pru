## Rafa Cabezas.

- Las rutas parecen estar como si estuviera todo organizado por carpetas y no hubiese sabido crear las carpetas desde github o algo. Entonces fallan las cosas y no se aplican los estilos, imagenes y demás.
> ¿Qué te ha pasado con las rutas y carpetas?

### HTML

+; error
*; detalle
^; positivo
    + Se entrega sin estilo por hoja mal enlazada. 
    * Titulo debe ser más especifico del contenido que está presentando (por ejemplo, Inicio - Sitio personal Rafa Cabezas). 
    ^ bien lang=es
    * Parece que en inicio usa para id camelcase y kebabcase pero luego no es consecuente en el resto de secciones.
        * eleccion de nombres mejorable para slider, sugerencia mas correcta:
            div.slider
                ul.slider-imges
                ul.slider-menu
    * Falta en una imagen el alt para accesibilidad (Se hubiese evitado pasando el validador)
    ^^ Muy bueno el slider

### CSS
    ^ comentarios
    * un font-size con valor sin unidad (Se hubiese evitado pasando el validador)
    * los colores podrían haber estado como variables para no tener que repetirlos
    + estilos evitables (línea 20)
    * habría que haber normalizado los estilos de lista
    ^^ buenísimo el uso de la pseudo-clase :target

### CONTENIDO

    * Inicio pobre (dos menus con distinto estilo)
        > Qué ha pasado con el doble navbar**

### PRESENTACION

^^ muy positivo la presentación del slide
    + estilo  pobre en el conjunto de la página.
    + falta consistencia en los estilos
    ^ formulario muy bien alineado y ordenado
    ^^ hay validación con required
    + se podría haber optimizado el uso de contenedores

### GENERAL
    * Necesita más consistencia en los contenedores y demás.
    * Uso de medidas relativas y absolutas, mejorable.