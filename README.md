# mo-captions
## ¿Qué es ésto?
Este repositorio contiene un índice de todas las charlas de [Mi Oficina Philatelic Society](https://mioficina.group) hasta la fecha indicada en cada release y los subtítulos en los idiomas soportados con enlaces directos al momento del video donde cada frase es pronunciada.

## ¿Para qué sirve ésto?
Existen múltiples formas de utilizar este recurso y cada una dependerá del tipo de uso que tu necesites darle. Te puedo mencionar algunos que se me ocurren, comenzando por mi propio uso principal:

- **Fuente de Investigación:** Descubrí que lo que me apasiona del coleccionismo, sea filatélico o cualquier otro, es investigar lo más que pueda sobre cada pieza. Por eso, y para el caso de la filatelia y áreas relacionadas, tener múltitud de referencias fácilmente consultables es clave para mis investigaciones. Debido a ésto, al ver la candidad de contenido que se estaba creando en Mi Oficina, supe que debía encontrar una forma de accesar efectivamente ese contenido. Así pues, estos archivos los tengo indexados en programas tipo [Qiqaa](https://github.com/jimmejardine/qiqqa-open-source) o [DocFetcher Pro](https://docfetcher.sourceforge.io/en/index.html) los cuales me permiten hacer búsquedas de texto completo (o _full-text search_), facilitándome muchísimo la búsqueda de información y, además, poder contextualizar esa información directamente en los videos.
- **Búsqueda Rápida:** A veces necesito ubicar algo que se dijo o que se pudo haber dicho en alguna charla. Hacer una búsqueda sencilla en cualquiera de los archivos de subtítulos permite ahorrarse una larga y tediosa búsqueda aleatoria.
- [**SEO:**](https://es.wikipedia.org/wiki/Posicionamiento_en_buscadores) Estos archivos propablemente ayuden a hacer más fácil encontrar información en los videos de Mi Oficina si se llegasen a integrar en alguna página web bien indexada por los búscadores web tipo Google.
- **Inspiración:** Lo mejor que pudiese ocurrir es que este proyecto sirva como inspiración para muchos otros, mejores y más completos que éste!

## ¿Cómo uso ésto?
- Si sabes usar git, probablemente no necesites esta ayuda. Have fun. Si no es así...
- Primero tienes que bajar o hacer _download_ del release más reciente de este proyecto en el o los idiomas que desees utilizar. Eso lo haces accediendo a la sección [**Releases**](https://github.com/willcastillo/mo-captions/releases) de este proyecto y luego haciendo _click_ en el archivo **mo.zip**.
- Una vez lo tengas en tu dispositivo, tendrás que utilizar alguna herramienta de descompresión para extrar los archivos del comprimido que bajaste. Te recomiendo extrarlo en su ubicación final. Probablemente puedas reemplazar los archivos de alguna versión anterior si la tuvieses, aunque recomiendo hacerlo sobre un directorio vacio.
- Abre el archivo index.html y comienza a usarlo!
- Si utilizas algún programa de indexación o búsqueda de texto completo (Qiqaa, DocFetcherPro...), tendrás que indicarle este directorio como una nueva fuente de datos.

## Lenguajes Soportados
Por los momentos, sólo está disponible en Español. Espero poder agregar Inglés próximamente. Por cierto, incluso para las charlas que fueron dadas originalmente en Inglés, sus subtítulos estarán en Español.

## Problemas Conocidos
**Integración:** La forma como estoy tomando los subtítulos no es la correcta. Estoy usando [yt-dlp](https://github.com/yt-dlp/yt-dlp). Eso tiene múltiples limitantes y no es escalable. La manera correcta es accesar los datos del canal de Mi Oficina mediante algún mecanismo de autenticación y autorización permitido (un API Key, un service account, OAuth...) Aún es muy pronto para invertir en esa via además de que habrían varios temas de seguridad que habría que sortear antes de implementarlo (y tener que ser previamente aprobado por los líderes de MO, por supuesto). Mientras tanto, iré actualizando estos índices cada tanto, probablemente una vez cada mes, con las charlas más recientes.

**Accesibilidad:** Intenté que los subtítulos de cada video fuesen fácilmente utilizables por personas con diferentes niveles de capacidad en ciertas áreas. Por ejemplo, mi intensión fue ser amigable con los lectores de pantalla, pero estoy muy lejos de ser un experto en esa área. Si tienen alguna sugerencia o comentario, mucho lo agradecería!

## Agradecimientos y Créditos
Mi agradecimiento a Mi Oficina Philatelic Society por esa hermosa labor que han estado haciendo en favor de la filatelia mundial. Éllos son una excelente razón para sentirme orgulloso de ser un filatelista latinoamericano.

El contenido de todos y cada uno de los subtítulos aquí presente son propiedad de cada uno de los ponentes, los cuales en la medida que el proyecto avance, se irán mencionando apropiadamente en los archivos apropiados. Asímismo, los comentarios, preguntas y respuestas al final de cada video/charla son propiedad y responsabilidad de quienes las emiten. Por limitantes técnicas, estas personas no podrán ser mencionadas en ningún archivo.
