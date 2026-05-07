# Guia de estudio: Arte, civilizacion y arte nacional

Sitio estatico para estudiar la consigna sobre la Generacion del 80, el concepto de arte y civilizacion, las instituciones artisticas argentinas y el surgimiento de un arte nacional.

## Ver localmente

Abrir `index.html` o `tema_arte_civilizacion_estudio.html` en el navegador.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub.
2. Enlazar este directorio con el remoto:

```bash
git remote add origin https://github.com/USUARIO/NOMBRE-DEL-REPO.git
git push -u origin main
```

3. En GitHub, ir a `Settings > Pages`.
4. En `Build and deployment`, elegir `Deploy from a branch`.
5. Seleccionar branch `main` y carpeta `/root`.
6. Guardar. GitHub Pages va a publicar el sitio en unos minutos.

## Estructura

- `index.html`: entrada para GitHub Pages.
- `tema_arte_civilizacion_estudio.html`: guia principal.
- `assets/`: imagenes usadas por la guia.
- `instructions.md`: contexto para continuar el trabajo con Codex.

## Nota sobre PDFs

Las carpetas `textos/` y `resumenes/` quedan ignoradas por Git para evitar publicar material de lectura o PDFs de circulacion interna en un sitio publico. Si el repositorio va a ser privado y queres versionarlas, elimina esas reglas de `.gitignore` antes de hacer `git add`.
