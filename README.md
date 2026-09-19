# B612 Web

Sitio web de B612 (centro de formación y producción artística).

## Estructura

- `public/` — código fuente del sitio (HTML/CSS/JS). Esto es exactamente lo que se publica en GitHub Pages.
- `.github/workflows/deploy.yml` — publica automáticamente el contenido de `public/` en GitHub Pages cada vez que se hace push a `main`.
- `conocimiento-b612.md` — base de conocimiento interna del proyecto (contexto de negocio, pendientes). **No se publica**: vive en la raíz del repo, fuera de `public/`.

## Desarrollo local

Abre `public/index.html` directamente en el navegador, o sirve la carpeta con cualquier servidor estático, por ejemplo:

```bash
npx serve public
```

## Publicación

1. Hacer push a la rama `main`.
2. El workflow de GitHub Actions construye y publica automáticamente el contenido de `public/`.
3. En GitHub, en **Settings → Pages**, configurar el origen ("Source") como **GitHub Actions** (no "Deploy from a branch").
