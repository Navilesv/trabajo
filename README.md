# Dashboard de Dotación FOSIS 2026

Dashboard interactivo de gestión de dotación, vacantes, riesgo organizacional y procedimientos del FOSIS.

## Cómo abrir

Abre **`Dashboard Dotación FOSIS.dc.html`** en un navegador (Chrome, Edge, Firefox).
Para publicarlo como página web: activa **GitHub Pages** en *Ajustes → Pages → Branch: `main`*.

## Contenido

- **`Dashboard Dotación FOSIS.dc.html`** — el dashboard (8 vistas).
- **`support.js`** — runtime necesario (no editar).
- **`docs/`** — documentos institucionales enlazados desde el dashboard (PDF, Word, Excel).
- **`data/`** — planillas fuente del análisis.

## Vistas

1. **Resumen** — KPIs, dotación real vs. autorizada, vacantes por categoría y prioridad.
2. **Dotación** — plantilla por unidad con brecha y score (ordenable).
3. **Nivel Central** — organigrama y dotación por subdirección.
4. **Vacantes** — 68 cargos con vía de provisión; clic para marcar provisto.
5. **Clima & Denuncias** — riesgo CEAL-SUSESO y denuncias Ley Karin (VALS).
6. **Seguimiento** — Hoja de Ruta DO 2026-2027 con estado editable.
7. **Procedimientos** — control de actualización por urgencia + registro de actualizaciones con archivo adjunto.
8. **Reportes** — descargas CSV e informe PDF imprimible.

## ⚠ Importante sobre los datos que registras

Los registros que ingresas en el dashboard (vacantes provistas, seguimiento, estados de
procedimientos y **archivos adjuntos**) se guardan **en el navegador de cada persona**
(localStorage / IndexedDB). **No se comparten entre equipos ni se suben a GitHub.**

Para un repositorio de datos **compartido por todo el equipo** se requiere un backend con
base de datos y autenticación (paso futuro).

---
*Fuentes: Nómina Mayo 2026 · Vacantes FOSIS · CEAL-SM/SUSESO 2025 · Sistema VALS · Cuadro de control de procedimientos 2026.*
