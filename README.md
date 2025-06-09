# FORMULARIOS HTML 

Contiene la evidencia sobre el formulario HTML el cual permite hacer un registro sobre los gustos musicales.

---

## index.html

**Estructura general:**
- `<!DOCTYPE html>`: Indica que el documento está escrito en HTML5.
- `<html lang="en">`: Inicia el documento HTML y especifica el idioma como inglés.
- `<head>`: Contiene metadatos como codificación, título y enlaces a estilos.
- `<meta charset="UTF-8" />`: Usa codificación UTF-8.
- `<meta name="viewport" ... />`: Permite diseño adaptable a dispositivos móviles.
- `<title>`: Título de la pestaña.
- `<link rel="stylesheet"...>`: Vincula la hoja de estilos.

**Cuerpo (`<body>`):**
- `<header>`: Encabezado principal de la página.
- `<nav>`: Menú secundario (en este caso solo muestra un subtítulo).
- `<main>` y `<section>`: Contenedor del formulario.

**Formulario (`<form>`):**
Cada bloque contiene:
- Etiqueta (`<label>`) que describe el campo.
- Campo de entrada (`<input>`, `select`, `textarea`).

Ejemplos:
- `Nombre` y `Apellido`: inputs con patrón de solo letras.
- `Correo`: tipo `email`.
- `Teléfono`: solo números con exactamente 10 dígitos.
- `Ciudad`: lista desplegable.
- `Géneros musicales`: casillas (`checkbox`). Uno de ellos muestra campo adicional si se marca "Otro".
- `Canciones al día`: campo numérico.
- `Playlist favorita`: campo tipo URL.
- `¿Dónde sueles escuchar música?`: opciones tipo radio.
- `Hora favorita`: campo de tipo hora.
- `Comentarios`: área de texto.
- `Imagen del artista`: permite cargar imagen.
- Botón de envío: con emoji 🚀.

**Script (`<script>`):**
- Función `mostrarOtroGenero()`: muestra campo extra si se selecciona "Otro".
- Evento `submit`: evita recarga, recopila datos y los muestra en el div `#resultado`, incluyendo la imagen del artista si se cargó.

---

## style.css

**Reglas generales:**
```css
* { box-sizing, padding, fuente general }
body { color, fondo, espacio }
```

**Estilos específicos:**
- `header h1`, `nav h2`: títulos centrados, colores y márgenes.
- `.container`: caja blanca centrada con sombra y bordes redondeados.
- `form`: layout en columna, espacio entre elementos.
- `.form-group label`: etiquetas en negrita.
- `input`, `select`, `textarea`: estilos consistentes, bordes suaves.
- `:focus`: resalta campo activo.
- `textarea`: redimensionable.
- `checkbox` y `radio`: tamaños y márgenes.
- `button`: diseño azul con efecto hover.
- `#resultado`: fondo verde claro, bordes, color de texto.
- `@media`: adapta estilos para pantallas pequeñas.

---

