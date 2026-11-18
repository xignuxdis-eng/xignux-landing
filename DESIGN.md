# XignuX — Design System

## Identidad visual
- **Concepto**: Taller gráfico CMYK moderno, claro por defecto con soporte de modo oscuro (`html.dark` persistido en `localStorage`).
- **Paleta accesible (WCAG AA >= 4.5:1)**:
  - Acento navegación / botones contorno: `#0056b3`
  - CTA principal CMYK (`.btn-cmyk`): gradiente `#006d99` → `#b30059` con texto `#ffffff`
  - WhatsApp (`.social-btn.whatsapp`, `.whatsapp-float`): `#15803d` con texto/ícono `#ffffff`
  - Instagram (`.social-btn.instagram`): gradiente `#b91c1c` → `#9d174d` → `#7e22ce` con texto `#ffffff`
  - Texto principal claro: `#0b1220` / secundario `#334155`

## Tipografía (`typeset`)
- **Display / Encabezados (`--font-display`)**: `Bricolage Grotesque` (600, 700, 800) con `letter-spacing: -0.02em`.
- **Cuerpo / UI (`--font-primary`)**: `DM Sans` (400, 500, 600, 700).

## Reglas de calidad
- Sin halos cromáticos ni `box-shadow` de neón (`dark-glow`); usar sombras neutras de elevación (`rgba(11, 18, 32, 0.18–0.34)`).
- Sin chips/eyebrows encima del `<h1>`.
- Jerarquía de encabezados continua (`h1` → `h2` → `h3`).
- Respetar `@media (prefers-reduced-motion: reduce)` desactivando animaciones continuas y scroll suave.
