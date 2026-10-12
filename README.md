# Estilo Urbano - Pre-Entrega Front-End

## Descripción del Proyecto:

Este proyecto es una página web de comercio de indumentaria (**tienda de ropa**) desarrollada como parte del curso de Front-End. La estructura está diseñada utilizando HTML semántico (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<table>`, `<footer>`) y cuenta con un diseño estilizado mediante CSS externo, aplicando Flexbox, CSS Grid y Media Queries para garantizar una completa adaptabilidad en dispositivos móviles y de escritorio.

---

## Características Principales:

1. **Estructura Semántica y Navegación:** Barra de navegación completa con enlaces de anclaje internos (`Inicio`, `Colección`, `Lookbook`, `Reseñas`, `Contacto`, `Registros`).
2. **Contenido Multimedia:** Inserción de logotipo institucional, imágenes de indumentaria y un video corporativo/desfile funcional equipado con controles y su respectiva pista de subtítulos (`subtitulos.vtt`).
3. **Tarjetas de Productos (Flexbox):** Contenedor organizado mediante Flexbox con tres cards de prendas de ropa (camperas, remeras, pantalones) detalladas con imagen, descripción, precios y botón interactivo de compra.
4. **Sección de Reseñas (CSS Grid):** Testimonios de clientes estructurados en una cuadrícula adaptable mediante CSS Grid.
5. **Formulario de Contacto (Formspree):** Formulario plenamente funcional integrado con Formspree para la recepción de consultas sobre talles y envíos.
6. **Tabla de Datos Históricos:** Registro de consultas anteriores de clientes que implementa celdas combinadas mediante la propiedad `colspan`.
7. **Diseño Adaptativo (Media Queries):** Reglas de adaptación responsiva configuradas para pantallas menores a 768px (móviles).

---

## Configuración del Formulario de Contacto (Formspree):

Para permitir que el formulario envíe correos electrónicos reales sin requerir un servidor backend propio (como Node.js o PHP), utilizamos **Formspree**.
