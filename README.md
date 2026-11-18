# Maqueta 3D · Mejoramiento del alumbrado — Vía de Ternera (Cartagena)

Maqueta digital interactiva del proyecto de mejoramiento del alumbrado público en la vía de Ternera (Cartagena, Colombia).

## Cómo desplegar en GitHub Pages

1. Crea un repositorio en GitHub (público).
2. Sube estos archivos a la raíz del repositorio:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
   - (opcional) `iniciar.bat` y carpeta `lib/`
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda. En unos segundos estará publicado en:
   `https://TU-USUARIO.github.io/TU-REPO/`

> **Nota:** No necesitas subir la carpeta `lib/` si usas CDN (jsDelivr). El `index.html` ya incluye un fallback automático a CDN si los archivos locales no existen.

## Cómo verlo localmente

**Opción A (con Python):**