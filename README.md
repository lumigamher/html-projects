# Temario de HTML Básico

## 1. Introducción a HTML

- Definición y propósito de HTML.
- Estructura básica de un documento HTML.

```html
htmlCopy code<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primer Documento HTML</title>
</head>
<body>
    <!-- Contenido de la página va aquí -->
</body>
</html>
```

## 2. Etiquetas HTML Básicas

- Encabezados (`<h1>`, `<h2>`, ..., `<h6>`).

```
htmlCopy code<h1>Encabezado de Nivel 1</h1>
<h2>Encabezado de Nivel 2</h2>
```

- Párrafos (`<p>`).

```
htmlCopy code
<p>Este es un párrafo de texto.</p>
```

- Enlaces (`<a>`).

```
htmlCopy code
<a href="https://www.ejemplo.com">Enlace de Ejemplo</a>
```

- Imágenes (`<img>`).

```
htmlCopy code
<img src="imagen.jpg" alt="Descripción de la imagen">
```

- Listas (`<ul>`, `<ol>`, `<li>`).

```
htmlCopy code<ul>
    <li>Elemento de lista 1</li>
    <li>Elemento de lista 2</li>
</ul>
```

## 3. Formateo de Texto

- Negrita (`<strong>`), Cursiva (`<em>`).

```html
htmlCopy code
<p><strong>Texto en negrita</strong> y <em>cursiva</em>.</p>
```

## 4. Estructura Semántica

- Secciones (`<header>`, `<footer>`, `<section>`, `<article>`).

```html
htmlCopy code<header>
    <h1>Encabezado de la Página</h1>
</header>
<section>
    <article>
        <h2>Título del Artículo</h2>
        <p>Contenido del artículo.</p>
    </article>
</section>
<footer>
    <p>Pie de Página</p>
</footer>
```

## 5. Formularios (`<form>`, `<input>`, `<button>`)

```html
htmlCopy code<form action="/procesar" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>

    <label for="email">Correo electrónico:</label>
    <input type="email" id="email" name="email" required>

    <button type="submit">Enviar</button>
</form>
```

## 6. Comentarios

- Uso de comentarios en HTML.

```html
htmlCopy code
<!-- Este es un comentario en HTML -->
```

## 7. Elementos Multimedia

- Videos (`<video>`), Audios (`<audio>`).

```html
htmlCopy code<video width="320" height="240" controls>
    <source src="video.mp4" type="video/mp4">
    Tu navegador no soporta el elemento video.
</video>
```

## 8. Tablas (`<table>`, `<tr>`, `<th>`, `<td>`)

```html
htmlCopy code<table>
    <tr>
        <th>Encabezado 1</th>
        <th>Encabezado 2</th>
    </tr>
    <tr>
        <td>Dato 1</td>
        <td>Dato 2</td>
    </tr>
</table>
```

## 9. Atributos Globales

- Atributos comunes que pueden ser usados en cualquier elemento HTML.

```html
htmlCopy code
<p id="parrafo1" class="destacado">Este es un párrafo con atributos</p>
```

## 10. Comentarios

- Comentarios en HTML.

```html
htmlCopy code
<!-- Este es un comentario en HTML -->
```

## 11. Enlaces Avanzados (`<a>`)

- Enlaces internos y externos.
- Enlaces a secciones dentro de la misma página.

```html
htmlCopy code
<a href="#seccion2">Ir a la Sección 2</a>
```

## 12. Caracteres Especiales

- Uso de entidades HTML para caracteres especiales.

```html
htmlCopy code
<p>&copy; 2024 Mi Empresa</p>
```

## 13. Formularios Avanzados

- Casillas de verificación (`<input type="checkbox">`).
- Botones de radio (`<input type="radio">`).
- Áreas de texto (`<textarea>`).

```html
htmlCopy code<input type="checkbox" id="opcion1" name="opcion1" value="opcion1">
<input type="radio" id="opcionA" name="grupoOpciones" value="opcionA">
<textarea id="mensaje" name="mensaje" rows="4" cols="50"></textarea>
```

## 14. Validación de Formularios

- Atributos `required`, `pattern`.

```html
htmlCopy code
<input type="text" id="codigoPostal" name="codigoPostal" required pattern="[0-9]{5}">
```

## 15. Elementos HTML5

- Nuevos elementos semánticos como `<nav>`, `<aside>`, `<figure>`, `<figcaption>`.

```html
htmlCopy code<nav>
    <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Acerca de</a></li>
    </ul>
</nav>
<figure>
    <img src="imagen.jpg" alt="Descripción de la imagen">
    <figcaption>Descripción de la imagen</figcaption>
</figure>
```

## 16. Estilos en línea y CSS

- Uso de estilos en línea.
- Vinculación de hojas de estilo externas.

```html
htmlCopy code<p style="color: blue; font-size: 16px;">Texto con estilos en línea</p>
<link rel="stylesheet" href="estilos.css">
```

## 17. Métodos de Codificación

- UTF-8 y otros métodos de codificación.

```html
htmlCopy code
<meta charset="UTF-8">
```

## 18. SEO Básico

- Uso de metaetiquetas para mejorar el SEO.

```html
htmlCopy code<meta name="description" content="Descripción de la página">
<meta name="keywords" content="HTML, tutorial, desarrollo web">
```