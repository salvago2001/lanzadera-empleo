# Lanzadera Nómada Cádiz R4 — Base de Datos

Aplicación web para consultar y filtrar la información de los participantes del programa **Lanzadera de Empleo Nómada Cádiz R4**.

🔗 **[Ver la web en vivo](https://salvago2001.github.io/lanzadera-empleo/)**

---

## Descripción

Esta herramienta permite a los orientadores y técnicos del programa acceder de forma rápida y sencilla a los perfiles profesionales de los participantes. Toda la información se presenta en un formato visual con tarjetas y fichas detalladas.

## Funcionalidades

- **Buscador de texto** — Búsqueda por nombre, ciudad, sector, puesto o capacidades (insensible a acentos)
- **Filtros combinables** — Ciudad, nivel de estudios, jornada, trabajo remoto y carnet de conducir
- **Selector de participante** — Desplegable directo para acceder a cualquier ficha
- **Vista tarjetas / tabla** — Dos modos de visualización intercambiables
- **Ficha detallada (modal)** — Datos personales, experiencia, preferencias, formación, competencias y objetivos
- **Navegación entre fichas** — Flechas anterior/siguiente y atajos de teclado (← →)
- **Diseño responsive** — Adaptado a escritorio, tablet y móvil

## Estructura del proyecto

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Aplicación web (HTML + CSS + JavaScript en un solo archivo) |
| `data.json` | Datos de los participantes en formato JSON |

## Actualizar los datos

Para añadir o modificar participantes:

1. Editar el archivo Excel original (`Cuestionario BASE DE DATOS.xlsx`)
2. Convertir los datos a formato JSON
3. Subir el nuevo `data.json` al repositorio

La web cargará automáticamente los datos actualizados sin necesidad de modificar `index.html`.

## Tecnologías

- HTML5 / CSS3 / JavaScript (vanilla)
- Sin dependencias externas ni frameworks
- Desplegado con GitHub Pages

---

*Desarrollado para el programa Lanzadera de Empleo Nómada — Cádiz*
