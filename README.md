# QB · Hub Ejecutivo

Landing page de Quiborax S.A. que centraliza acceso a los dashboards ejecutivos:

- **[Dashboard de Costos](https://quiborax-costos.vercel.app)** — Costos unitarios, totales, materia prima y comparativo real vs presupuesto
- **[Intel · Compras](https://intel-compras.vercel.app)** — Inteligencia de proveedores y precios
- **[Estado de Resultados](https://quiborax-eerr.vercel.app)** — EERR mensual con EBITDA y resultado financiero

## Stack

Single-file HTML estático. Sin dependencias de build. Embebe logo QB en base64.

## Deploy

Producción: **https://quiborax-hub.vercel.app**

Push a `main` → auto-deploy en Vercel.

## Estructura

```
.
├── index.html      # Hub completo (HTML + CSS + JS inline)
├── vercel.json     # Config Vercel (static site)
└── README.md
```
