# Framework de Contenido Semántico - BonusGratis

## 1. Propósito del Proyecto

Este repositorio sirve como un "framework" o plantilla base para crear y gestionar contenido web que sea altamente legible para agentes de Inteligencia Artificial (IA). El enfoque principal es el uso de **JSON-LD** para incrustar datos estructurados semánticamente dentro de páginas HTML estáticas.

El objetivo es poder añadir nuevo contenido de forma modular, asegurando que cada pieza de contenido esté acompañada de sus correspondientes metadatos estructurados.

## 2. Estructura del Framework

- **`index.html`**: El punto de entrada principal. Contiene la estructura del contenido visible y el bloque JSON-LD en la cabecera.
- **`css/style.css`**: Hoja de estilos para la presentación visual. Está separada del contenido para facilitar el análisis de la estructura.
- **`README.md`**: Este archivo. Proporciona la documentación del framework.

## 3. Primer Contenido: Enlace de Llamada a la Acción

Como punto de partida, la página `index.html` contiene un único enlace (link) que se visualiza como un botón. El script JSON-LD describe esta página y la acción asociada al botón (`LinkAction`), especificando la URL de destino de una manera que las máquinas pueden entender.

## 4. Cómo Añadir Nuevo Contenido

Para añadir nuevo contenido, se debe:
1.  Crear una nueva página HTML o añadir una nueva sección (`<section>`) al `index.html`.
2.  Añadir el contenido visible (texto, imágenes, enlaces).
3.  Actualizar o añadir un nuevo bloque `<script type="application/ld+json">` que describa el nuevo contenido utilizando vocabularios estándar (ej. Schema.org).
