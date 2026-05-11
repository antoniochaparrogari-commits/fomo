# FOMO Santanyi · POS

Punto de venta para Fomo Santanyi Cheesecake.

## Características

- Datos persistentes (localStorage) — sobrevive a refrescos, cierres de app y reinicios
- Histórico de cierres por día, semanal y mensual
- Exportar CSV de todas las ventas
- Funciona sin internet (service worker)
- Instalable como app (PWA) con icono propio

## Instalar en iPhone

1. Abrir la URL de GitHub Pages en **Safari**
2. Botón **Compartir** → **"Añadir a pantalla de inicio"**
3. Aparece como **FOMO**

## Datos

Se guardan localmente en el móvil. Exporta CSV regularmente como backup.

## Archivos

- `index.html` — app
- `manifest.json` — config PWA
- `sw.js` — service worker (offline)
- `icon-180.png`, `icon-192.png`, `icon-512.png` — iconos
