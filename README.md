---
sdk: static
colorFrom: blue
colorTo: gray
title: Landing Profesional – Plantilla Web Estática
description: Página única, responsiva y lista para vender plantillas web profesionales. Incluye hero, servicios, portafolio y formulario de contacto.
---

# professional-landing-page

Esta es una **plantilla estática** de una landing page profesional pensada para ser vendida a clientes que necesiten una presencia web elegante y lista para personalizar.

## Características

- **Una sola página** (`index.html`) con todo el CSS y JavaScript embebidos.
- **Diseño responsive**: 3 columnas en desktop, 2 en tablet y 1 en móvil.
- **Tipografía**: *Montserrat* (display) + *Open Sans* (texto) de Google Fonts.
- **Paleta de colores**: azul marino, blanco y gris claro.
- **Hero** con imagen de fondo de alta resolución y CTA “Solicitar propuesta”.
- **Sección de servicios** con tarjetas con iconos SVG.
- **Portafolio** con filtro por categoría y lightbox.
- **Formulario de contacto** en modal (envía datos a `/contact` vía AJAX; el backend debe implementarse con Flask).
- **Botón “Comprar ahora”** enlazado a Stripe Checkout (URL configurable).
- **Footer** con enlaces legales y redes sociales.
- **SEO**: meta tags, Open Graph y archivo `sitemap.xml` incluido.
- **Google Analytics**: script de carga asíncrona (código configurable).
- **Accesibilidad**: foco visible, `prefers-reduced-motion`, ARIA roles en modal y lightbox.

## Estructura de archivos