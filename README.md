# Cervecería El Ángel — propuesta de web

Repositorio con tres piezas:

1. **`REQUISITOS.md`** — análisis completo del negocio y de lo que la web tiene que resolver.
2. **`NOTEBOOKLM_PROMPT.md`** — guía y prompts para usar NotebookLM y generar presentaciones, infografías, cápsulas para Reels y demás material visual.
3. **`index.html` + `assets/`** — web estática de prueba, lista para servir en cualquier hosting (incluido GitHub Pages).

## Ver la web en local

Abre `index.html` directamente en el navegador, o sirve la carpeta con cualquier servidor estático, p. ej.:

```powershell
python -m http.server 8080
# luego abre http://localhost:8080
```

## Publicar en GitHub Pages

1. Crea un repo en GitHub (público) y empuja `main`.
2. En el repo: **Settings → Pages**.
3. En **Source** elige `Deploy from a branch`.
4. **Branch:** `main` · **Folder:** `/ (root)` · **Save**.
5. En 1–2 minutos GitHub muestra la URL en `https://<usuario>.github.io/<repo>/`.

> Si más adelante quieres dominio propio (recomendado por SEO), apunta el DNS a GitHub Pages y configura un `CNAME` en este mismo repo.

## Estructura

```
.
├─ index.html
├─ assets/
│  ├─ css/styles.css
│  ├─ js/main.js
│  └─ img/favicon.svg
├─ REQUISITOS.md
├─ NOTEBOOKLM_PROMPT.md
└─ README.md
```

## Siguientes pasos

- Cambiar los placeholders de la galería por fotos reales del local y de los platos.
- Sustituir el contenido de la sección "Carta" por el menú de la semana actual o por un PDF descargable.
- Conectar el formulario de contacto a un servicio (Formspree, Netlify Forms, etc.) si se decide aceptar reservas online.
- Comprar y vincular un dominio propio (`cerveceriaelangel.es` o similar).
