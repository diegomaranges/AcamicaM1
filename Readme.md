# INFO A TENER EN CUENTA

## HTML

### IMPORTANCIA DE LOS TAGS
Esencialmente nosotros como programadores podemos usar cualquier tag que queramos y hacer que la pagina tenga una correcta funcionalidad. Sin embargo la separación utilizando los correctos tags nos permiten a nosotros poder distinguir con mayor facilidad que queremos desarrollar en cada sección de la pagina, sin crear un ambiente ultra ambiguo para nosotros, el navegador y las partes relacionadas.
Con una buena implementación de los mismos una pagina puede ser entendida de una mejor manera y por eso es importante tener en cuenta la gran variedad de separadores que poseemos.

### METADATA
Las etiquetas meta o meta tags encabezan un documento HTML y suministran información codificada a navegadores y motores de búsqueda sobre una página web. Los metadatos son invisibles para el usuario y se encargan de añadir información para facilitar el análisis de los archivos HTML y la gestión del contenido de una página web. Los meta tags de HTML siguen a menudo la misma construcción: en primer lugar se define un elemento y en segundo lugar se asigna un contenido. De esto resulta el siguiente esquema:

<meta name="Nombre del elemento" content="Contenido asignado"/>

Hace un tiempo, los metadatos eran de gran importancia para el SEO, ahora su influencia en el posicionamiento en los buscadores más conocidos ha disminuido. Sin embargo, los meta tags siguen siendo relevantes para metabuscadores y archivos de búsqueda locales, por lo que no está de más contar con una detallada lista de los mismos. Además, permiten definir indicaciones para guiar a los bots (crawlers) de los motores de búsqueda.

La lista de todos los elementos que se pueden incluir en el encabezado de un archivo HTML es larga. Junto a datos esenciales como el título y la descripción de la página o la definición de la fuente usada para el texto, el header de los archivos HTML puede abarcar información útil para los agentes de usuario. Así, es posible delimitar palabras clave relevantes o definir un tema para la página. Incluso se puede hacer referencia al autor o editor de los contenidos e indicar el copyright. Aunque estos datos no siempre son relevantes para la interacción con navegadores y motores de búsqueda, los meta tags dirigen su comportamiento impidiendo, por ejemplo, la indexación de un archivo HTML o el rastreo de los enlaces de una página. En la siguiente selección aclaramos las etiquetas meta más importantes y su utilidad para la administración de páginas web.

### DIV vs SECTION vs ARTICLE
Los tres cumplen la misma función ya que todos están pensados para dividir en moduloso mas pequeños y manejables para nosotros.
Todos se utilizan para facilitar la implementación de nuestro código css en el, por lo cual no hay diferencia entre ellos, porque el contenido no lo definen ellos propiamente dicho.
En general div es utilizado cuando el contenido no esta relacionado entre si, es decir si tenemos que definir en alguna parte de nuestra pagina dos bloques diferentes con sus estilos y la información, de cada uno es variada y no relacionada. En el caso que la información sea sobre el mismo tema y pueda considerarse completamente autónoma se utiliza article. Y en cualquier otro caso utilizamos section.
En esencia podríamos decir que article es mas especifico que section y section es mas especifico que div.

### LINKS RECOMENDADOS

1. [Explicación sobre la semántica de html (ingles)](https://seekbrevity.com/semantic-markup-important-web-design/)
2. [Lista de tags (ingles)](https://www.w3schools.com/TAGS/default.ASP)
3. [Meta tags mas importantes](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/los-meta-tags-mas-importantes-y-su-funcion/)
4. [Div, section o article (ingles)](https://bitsofco.de/sectioning-content-in-html5/)
5. [input-type-button-vs-button](https://es.stackoverflow.com/questions/79603/input-type-button-vs-button-en-html)

## CSS

### PRIORIDAD(especificidad) Y SELECTORES

La especificidad es un peso (importancia o valor) que se le asigna a una declaración CSS dada, determinada por el número correspondiente de cada tipo de selector. Cuando varias declaraciones tienen igual especificidad, se aplicará al elemento la última declaración encontrada en el CSS. La especificidad solo se aplica cuando el mismo elemento es objetivo de múltiples declaraciones. Según las reglas de CSS, en caso de que un elemento sea objeto de una declaración directa, esta siempre tendrá preferencia sobre las reglas heredadas de su ancestro.
Dentro de los selectores tenemos por tipo, pseudo elements, clases, atributos, pseudo clases y ids. además de que se pueden considerar en esta parte también los atributos stryle en el código html y el important! (se recomienda no utilizar).
Recordar usar la tabla para ver cual selector se aplica y recordar que cuando se tiene la misma importancia se aplica el ultimo cambio:
![calcular prioridad](C:\Users\diego\Documents\GitHub\AcamicaM1\unnamed.jpg)

### FUENTES(TIPOGRAFIA)

Las tipografías (*también denominadas fuentes*) son una parte muy importante del mundo de CSS. De hecho, son uno de los pilares del diseño web. La elección de una **tipografía adecuada**, su tamaño, color, espacio entre letras, interlineado y otras  características pueden variar mucho, de forma consciente o inconsciente, la percepción en la que una persona interpreta o accede a los  contenidos de una página.

### POSITION, DISPLAY Y FLOAT



### FLEX + GRID

La diferencia básica entre Grid y Flexbox Layout es que Flexbox se creó para diseños de una dimensión, en una fila o una  columna. En cambio CSS Grid Layout se pensó para el diseño  bidimensional, en varias filas y columnas al mismo tiempo.

### ANIMATION

### GENERATORS

1. [flexbox](https://loading.io/flexbox/)
2. [grid](https://cssgrid-generator.netlify.app/)

### RESPONSIVE


### TIPS

### LINKS RECOMENDADOS
1. [Selectores muy buenos y bien explicados](https://code.tutsplus.com/es/tutorials/the-30-css-selectors-you-must-memorize--net-16048) 
2. [Teoría de selectores (ingles)](https://www.freecodecamp.org/news/css-selectors-cheat-sheet/)
3. [Especificidad (ingles)](https://developer.mozilla.org/es/docs/Web/CSS/Especificidad)
4. [Tipografías]( https://lenguajecss.com/css/fuentes-y-tipografias/tipografias/)
5. [CSS Position, Display y Float (ingles)](https://medium.com/@mautayro/understanding-css-position-display-float-87f9727334b2)
6. [Google fonts (ingles)]( https://fonts.google.com/)
7. [Grid y flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout/Relacion_de_Grid_Layout)
8. [Hermoso y muy completo articulo de flexbox y grid (Grid for layout, Flexbox for components)(ingles)](https://ishadeed.com/article/grid-layout-flexbox-components/)
9. [Definición de layouts y componentes](https://stackoverflow.com/questions/44309390/whats-exactly-the-purpose-of-components-layouts-and-pages-folders-in-a-meteor)

## EJ