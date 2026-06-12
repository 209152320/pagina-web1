# Tarea 03 — Pieza narrativa individual en HTML
 
## Descripción
 
Este repositorio contiene mi trabajo individual para el proyecto grupal sobre el deshielo glaciar en Chile, desarrollado para el curso **Narración Gráfica** de la Universidad Católica de Chile.
 
La pieza se construyó a partir de los datos del **Inventario Público de Glaciares 2022 (IPG 2022)** de la Dirección General de Aguas (DGA) y tiene como foco las **10 cuencas con mayores reservas de agua glaciar en Chile**, analizando su distribución geográfica y su relación con la crisis hídrica nacional.
 
**Sitio publicado en GitHub Pages:** [link aquí][(https://209152320.github.io/pagina-web1/)](https://209152320.github.io/Tarea-03/)
 
---
 
## Estructura del repositorio
 
```
/
├── docs/
│   ├── index.html       # Página principal de la pieza narrativa
│   └── vis03.jpg        # Imagen de la visualización (IPG 2022)
└── README.md            # Este archivo
```
 
---
 
## Contenido de la página
 
- Crónica narrativa sobre la distribución del agua glaciar por cuenca en Chile
- Tarjetas con datos clave del IPG 2022
- Visualización: Top 10 cuencas con mayores reservas de agua glaciar
- Lista detallada de las cuencas del ranking con sus volúmenes
- Preguntas que guían la investigación grupal
- Fuentes y enlaces a los datos originales
---
 
## Proceso
 
Para esta tarea partí revisando la visualización que había construido en la entrega anterior: un gráfico de barras horizontales con las 10 cuencas con más agua glaciar equivalente, elaborado con Altair a partir del IPG 2022 limpio.
 
Lo primero que noté al mirar el gráfico fue que todas las cuencas del top 10 estaban en el extremo sur del país. Eso me pareció el ángulo más interesante para contar: Chile tiene una enorme reserva de agua glaciar, pero está concentrada en la Patagonia, lejos de donde más se necesita. Desde ahí construí la crónica, cruzando ese dato geográfico con el contexto de la megasequía en la zona central.
 
Para estructurar el HTML definí primero las secciones que tendría la página: encabezado, tarjetas de datos, crónica, visualización, lista de cuencas y fuentes. Eso me ayudó a tener claro qué etiquetas usar antes de escribir el código.
 
Usé las etiquetas vistas en clases (`<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<div>`, `<figure>`, `<blockquote>`, listas ordenadas y no ordenadas) y busqué algunas adicionales como `<figcaption>` para describir la imagen y el atributo `rel="noopener"` en los links externos.
 
El estilo visual lo pensamos desde el principio como algo llamativo y con personalidad, pero emotivo: fondo claro, colores similares a los glaciares y tipografía Playfair display para los títulos, buscando que la página se sintiera distinta a una página web genérica sin por eso perder claridad en la lectura.
 
---
 
## Fuente de datos
 
- [Inventario Público de Glaciares 2022 — DGA](https://dga.mop.gob.cl/inventario-publico-de-glaciares-actualizacion-2022/)
- [Fundación Glaciares Chilenos — Análisis IPG 2022](https://www.glaciareschilenos.org/reportajes/glaciares-chilenos-en-evolucion-analisis-del-inventario-publico-de-glaciares-2022/)
