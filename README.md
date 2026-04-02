# BaumApp CRM Pipeline

CRM de gestión comercial y pipeline de ventas para **BaumApp** y **BaumSystem**.

Aplicación 100% client-side en un solo archivo HTML — sin backend, sin dependencias externas más allá de Chart.js y Google Fonts.

## Características

- **Pipeline Kanban** con 6 etapas y drag & drop
- **Dual plataforma**: BaumApp (SaaS) y BaumSystem (Agrícola), datos independientes con sincronización unidireccional
- **Dashboard** con KPIs, gráficos de embudo, comparativo metas vs real 2026
- **Gestión de clientes** con ficha completa (info, comercial, actividad, seguimiento)
- **Tarifario editable** con calculadora de tarifas y cotización con implementación
- **Reuniones** con integración Google Calendar, historial y actividad por cliente
- **Análisis** de ARR/MRR con registro semanal
- **Exportación CSV** contextual por módulo
- **Autenticación** por correo electrónico con gestión de usuarios
- **Persistencia** en localStorage del navegador

## Uso

1. Abre `index.html` en tu navegador o despliega en GitHub Pages
2. Ingresa con: `b.sepulveda@baumsystem.com` / `Baum2025!`

## Deploy en GitHub Pages

1. Crea un repositorio en GitHub
2. Sube `index.html` a la rama `main`
3. Ve a **Settings → Pages → Source**: selecciona `main` / `/ (root)`
4. Tu CRM estará disponible en `https://tu-usuario.github.io/tu-repo/`

## Stack

- HTML5 + CSS3 + JavaScript vanilla
- [Chart.js 4.4.1](https://www.chartjs.org/) para visualizaciones
- [Nunito](https://fonts.google.com/specimen/Nunito) (Google Fonts)
- localStorage para persistencia de datos
- SVG inline para iconografía minimalista

## Licencia

Proyecto privado de BaumSystem SpA.
