# Documento de defensa oral - 1er Parcial

## Ejercicio integrador (portfolio: `index.html`, `biografia.html`, `style.css`)

### Recurso: etiquetas semanticas (`header`, `main`, `section`, `nav`, `footer`, `article`)
- Que es y como se usa: son etiquetas de HTML5 que separan el contenido segun su funcion real.
- Justificacion: las use porque la consigna pide semantica correcta y asi el documento queda claro para navegadores y docentes.
- Alternativas: se podria usar `div` con clases, pero semantica pierde claridad.
- Otras formas: combinar algunas secciones dentro de `article` si el contenido fuese mas narrativo.

### Recurso: galeria con enlaces
- Que es y como se usa: un conjunto de imagenes miniatura dentro de links (`a`) que llevan a cada ejercicio.
- Justificacion: permite navegar rapido a los 5 trabajos desde un solo punto.
- Alternativas: lista textual de links sin miniaturas.
- Otras formas: usar tarjetas con titulo + descripcion + boton.

### Recurso: CSS externo
- Que es y como se usa: hoja `style.css` enlazada con `link`.
- Justificacion: separa estructura (HTML) de presentacion (CSS) y cumple la consigna.
- Alternativas: estilos internos en `style`, menos recomendado.
- Otras formas: modular CSS en varios archivos por seccion.

### Recurso: diseno adaptable con `max-width: 960px`
- Que es y como se usa: limita el ancho del contenedor central para que no se estire de mas.
- Justificacion: el parcial lo pide explicitamente.
- Alternativas: `width: 90%` sin limite maximo.
- Otras formas: usar `clamp()` para anchos dinamicos.

### Recurso: Flexbox para galeria y redes
- Que es y como se usa: `display: flex`, `flex-wrap`, `gap`, `justify-content`.
- Justificacion: facilita alinear miniaturas en fila y adaptarlas a diferentes pantallas.
- Alternativas: `display: inline-block` o `float` (mas antiguo y menos prolijo).
- Otras formas: CSS Grid para un layout mas estricto por columnas.

## Ejercicio 01 (archivo original enlazado)
### Recurso clave observado: estructura base de perfil con secciones
- Que es y como se usa: organizacion por bloques con titulos y parrafos.
- Justificacion: sirve para practicar semantica y lectura ordenada.
- Alternativas: una sola seccion larga con anclas internas.
- Otras formas: version tipo CV con tabla (menos recomendado hoy).

## Ejercicio 02 (archivo original enlazado)
### Recurso clave observado: contenido editorial con `article`, `figure`, `figcaption`, `aside`
- Que es y como se usa: etiquetas para notas con imagen y contenido complementario.
- Justificacion: refleja una estructura de blog real.
- Alternativas: usar solo `p` + `img` sin `figure`.
- Otras formas: dividir en multiples `article` por cada escena del viaje.

## Ejercicio 03 (archivo original enlazado)
### Recurso clave observado: pagina de producto con listas y testimonios (`blockquote`)
- Que es y como se usa: `ul` para caracteristicas y `blockquote` para opiniones.
- Justificacion: mejora escaneo visual de datos de producto.
- Alternativas: parrafos corridos para todo (menos legible).
- Otras formas: tabla comparativa entre modelos.

## Ejercicio 04 (archivo original enlazado)
### Recurso clave observado: portal de noticias con varias categorias
- Que es y como se usa: secciones por rubro (`nacional`, `internacional`, etc.) y enlaces externos con `target="_blank"`.
- Justificacion: separa bien las areas tematicas.
- Alternativas: una unica lista cronologica de noticias.
- Otras formas: portada + detalle por noticia en paginas separadas.

## Ejercicio 05 (archivo original enlazado)
### Recurso clave observado: maquetado con Flexbox
- Que es y como se usa: distribucion horizontal de tarjetas y ajuste por `wrap`.
- Justificacion: era el objetivo del ejercicio y permite respuesta rapida en distintos anchos.
- Alternativas: CSS Grid con columnas repetidas.
- Otras formas: media queries con bloques apilados segun breakpoints.

## Preguntas tipicas para practicar oral
1. Por que elegiste HTML semantico en vez de usar `div` para todo?
2. Como aseguraste accesibilidad en imagenes y enlaces?
3. Que ventaja te dio Flexbox en la galeria?
4. Como justificas la paleta y tipografias del moodboard?
5. Si el docente pide otra resolucion, como migrarias de Flexbox a Grid?
