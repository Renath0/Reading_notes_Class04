# Reading_notes_Class04
## Sitio Web con HTML puro desde cero

### ¿Qué es HTML y por qué lo usamos? ###
HTML, es un acrónimo cuyo significaod es HyperText Markup Language (Lenguaje de Marcado de Hipertexto), es el lenguaje estándar utilizado para crear y diseñar páginas web. Se compone de una serie de etiquetas que describen la estructura y el contenido de una página web, permitiendo la inclusión de texto, imágenes, enlaces, formularios y otros elementos multimedia.

**Lo usamos porque**
  1. Define una estructura de página
  1. Facilita la creación de hipervínculos
  1. Permite la integración de archivos multimedia

### ¿Cuáles son las 3 partes principales de un elemento HTML? ###

  1. **Etiqueta de apertura:** Define el tipo de elemento que se está utilizando, como por ejemplo:
```
<p> para un párrafo.
<a> para un enlace.
<img> para una imagen.
```
  2. **Contenido:** Es la información dentro del elemento HTML, que puede incluir texto, otros elementos HTML, imágenes, enlaces, etc. Por ejemplo:
```
<p> Este es un párrafo </p>
```

  3. **Etiqueta de cierre:** Se utiliza para cerrar el elemento que se abrió anteriormente. Tiene el mismo nombre que la etiqueta de apertura, pero con la diferencia de que se agrega una barra inclinada ("/"). 
Por ejemplo:
```
</p> 
```

### ¿Cómo se llama cuando le das información extra a un elemento? ###
Se llama atributos, esto sirve para proporcionar información adicional a un elemento, los atributos afectan a la apariencia del elemento, por ejemplo:
```
<img src="imagen.jpg" alt="Descripción de la imagen">
```

### ¿Qué es un elemento semántico? ###
Un elemento semántico se puede entender como una etiqueta que describe el significado de su contenido para los navegadores web, dándole un formato al contenido,
```
<header>: Es el encabezado de la página web.
<nav>: Define la sección de navegación de la página web.
<main>: Representa el contenido principal de la página web.
<section>: Define una sección genérica dentro de la página web.
```
