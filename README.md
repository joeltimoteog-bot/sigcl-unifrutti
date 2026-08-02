# SIGCL · Sistema Inteligente de Clima Laboral — UNIFRUTTI PERÚ

Frontend estático (GitHub Pages). El backend es una aplicación web de
Google Apps Script que guarda cada encuesta en la hoja **Base de Clima Laboral**.

## Configuración
1. Desplegar `Code.gs` como Aplicación web (Ejecutar como: Yo · Acceso: Cualquier persona).
2. Copiar la URL `/exec` y pegarla en `config.js` → `window.SIGCL_API`.
3. `git add . && git commit -m "config api" && git push`

## URLs
- Sistema / dashboard: `https://<usuario>.github.io/sigcl-unifrutti/`
- Encuesta directa (QR): `https://<usuario>.github.io/sigcl-unifrutti/?e=1`
- Modo capacitación (datos de ejemplo): `.../?demo=1`

Gestión Humana · Relaciones Laborales · Enterprise 2026
