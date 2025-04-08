Documentación de Etiquetas HTML Utilizadas
1. Estructura Básica y Metadatos
<!DOCTYPE html>
Define el tipo de documento (HTML5). Es obligatorio para que el navegador interprete correctamente el HTML.

<html lang="es">
Elemento raíz del documento. El atributo lang="es" indica que el contenido está en español, lo que favorece la accesibilidad y el SEO.

<head>
Contiene metadatos e información relevante para el navegador, como el conjunto de caracteres y enlaces a hojas de estilo.

<meta charset="UTF-8">
Establece la codificación de caracteres a UTF-8, lo que permite mostrar adecuadamente caracteres especiales y acentos.

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Configura la ventana gráfica para una correcta visualización y adaptación en dispositivos móviles, estableciendo el ancho de la pantalla y el nivel de zoom inicial.

<title>
Define el título del documento que se muestra en la pestaña del navegador.

<link rel="stylesheet" href="styles.css">
Enlaza un archivo CSS externo (styles.css) para aplicar estilos al HTML.

2. Estructura del Contenido
<body>
Contiene todo el contenido visible de la página.

Encabezado y Navegación
<header>
Representa la cabecera de la página y suele incluir elementos de navegación o la información principal del sitio.

<nav>
Elemento de navegación que agrupa enlaces de menú o navegación interna.

<ul>
Lista no ordenada. Se utiliza aquí para agrupar los elementos del menú.

<li>
Elemento de lista. Cada uno representa un vínculo de navegación dentro del <ul>.

<a href="#...">
Hipervínculo. El atributo href define el destino (en este caso, anclas dentro de la misma página).

<h1> y <h2>
Encabezados o títulos. <h1> es el más importante (generalmente el título principal) y <h2> se usa para subtítulos o secciones.

Contenido Principal
<main>
Indica la sección principal del contenido de la página. Es útil para la accesibilidad, permitiendo que los lectores de pantalla salten directamente al contenido relevante.

<section>
Define secciones temáticas dentro del contenido. Se utiliza para agrupar artículos o partes relacionadas.

<article>
Representa un bloque o entrada de contenido independiente, como un post de blog o una entrada informativa.

<header> (dentro de article y section)
Se vuelve a usar para titular o introducir el contenido específico de ese bloque.

<p>
Párrafo. Utilizado para bloques de texto.

<figure>
Agrupa elementos gráficos (como imágenes) y su pie de foto, facilitando la asociación semántica entre ellos.

<img src="..." alt="...">
Etiqueta para insertar una imagen. El atributo src especifica la ruta de la imagen y alt proporciona una descripción alternativa para accesibilidad.

<figcaption>
Proporciona una leyenda o descripción para el contenido dentro del <figure>.

<aside>
Contenido relacionado, pero no central. Normalmente se utiliza para información complementaria o de interés adicional, por ejemplo, datos curiosos o publicidad.

<details>
Permite ocultar o mostrar información adicional interactiva, útil para secciones que pueden expandirse o contraerse.

<summary>
Título o resumen visible de un elemento <details>, indicando qué contiene la información oculta.

<time datetime="YYYY-MM-DD">
Indica un instante o rango de tiempo. El atributo datetime contiene una fecha u hora en formato ISO.

<mark>
Resalta o marca un texto importante, visualmente destacándolo del resto del contenido.

Formularios
<form action="#" method="post">
Contenedor para elementos interactivos y de entrada de datos. Los atributos action y method definen a dónde se enviarán y cómo se enviarán los datos.

<fieldset>
Agrupa elementos relacionados dentro de un formulario. Proporciona una estructura visual y semántica para conjuntos de campos.

<legend>
Etiqueta el contenido agrupado dentro de <fieldset>, describiendo el propósito del grupo.

<label>
Etiqueta para elementos de formulario. Asociada a un control mediante el atributo for que debe coincidir con el id del elemento correspondiente.

<input>
Elemento de entrada para la obtención de datos. En el ejemplo se utilizan los tipos "text" y "email" para diferentes formatos de datos.

<textarea>
Campo de texto de múltiples líneas, útil para mensajes o comentarios.

<button>
Botón interactivo para enviar formularios o ejecutar acciones.

Pie de Página
<footer>
Representa el pie de página del documento o de una sección, donde se coloca información como derechos de autor, enlaces o datos de contacto.