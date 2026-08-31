# Micks — Productos Naturales

Sitio web de la marca Micks (barras de cereal, brownies, galletas y granola bars).

## Estructura
```
micks-site/
├── index.html
├── css/style.css
├── js/script.js
├── images/          → logo, etiquetas y fotos de producto
└── README.md
```

## Cómo publicarlo en GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `micks-web`).
2. Subí todo el contenido de esta carpeta al repositorio:
   ```bash
   cd micks-site
   git init
   git add .
   git commit -m "Sitio Micks"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/micks-web.git
   git push -u origin main
   ```
3. En GitHub, entrá a **Settings → Pages**.
4. En "Branch" elegí `main` y la carpeta `/ (root)`, luego **Save**.
5. En un par de minutos tu sitio va a estar en:
   `https://TU-USUARIO.github.io/micks-web/`

## Editar contenido
- Textos y secciones: `index.html`
- Colores y estilos: `css/style.css` (todos los tonos están arriba de todo, en `:root`)
- Teléfono / redes: buscá `2613844120` y `@daisakmicks` en `index.html` y reemplazá donde haga falta.
- Imágenes: reemplazá los archivos dentro de `images/` manteniendo el mismo nombre, o cambiá las rutas en `index.html`.
