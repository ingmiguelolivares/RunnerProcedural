# Runner Procedural Music

Export WebGL de un proyecto hecho en Unity, listo para publicarse como sitio estático.

## Contenido

- `index.html`: punto de entrada de la aplicación.
- `Build/`: archivos generados por Unity para WebGL.
- `TemplateData/`: estilos, imágenes y recursos de la plantilla de Unity.

## Ejecutarlo en local

Como es una app WebGL, conviene abrirla con un servidor local:

```bash
python3 -m http.server 8000
```

Luego abre `http://localhost:8000`.

## Subirlo a GitHub

Este repositorio ya está estructurado para subir directamente:

1. Asegúrate de incluir `index.html`, `Build/` y `TemplateData/`.
2. Haz commit de los cambios.
3. Sube el repositorio a GitHub.

## Publicarlo con GitHub Pages

Si quieres publicarlo desde GitHub Pages, este mismo contenido puede servir como sitio estático.
