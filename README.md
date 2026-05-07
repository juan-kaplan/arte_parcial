# Guia de estudio: Arte, civilizacion y arte nacional

Sitio estatico para estudiar la consigna sobre la Generacion del 80, el concepto de arte y civilizacion, las instituciones artisticas argentinas y el surgimiento de un arte nacional. Tambien incluye secciones breves para las consignas alternativas y una vista visual de apoyo.

## Ver localmente

Abrir `index.html`, `tema_arte_civilizacion_estudio.html` o `presentacion.html` en el navegador.

## Publicar en GitHub Pages

El repo ya esta preparado para GitHub Pages desde `main` y carpeta `/root`. Despues de cada cambio:

```bash
git add .
git commit -m "Descripcion breve"
git push
```

GitHub Pages publica el sitio en unos minutos.

## Estructura

- `index.html`: entrada para GitHub Pages.
- `tema_arte_civilizacion_estudio.html`: guia principal.
- `presentacion.html`: vista secundaria para repasar con imagenes grandes, palabras clave y bullets.
- `assets/`: imagenes usadas por la guia.
- `instructions.md`: contexto para continuar el trabajo con Codex.

## Nota sobre PDFs

Las carpetas `textos/` y `resumenes/` quedan ignoradas por Git para evitar publicar material de lectura o PDFs de circulacion interna en un sitio publico. Si el repositorio va a ser privado y queres versionarlas, elimina esas reglas de `.gitignore` antes de hacer `git add`.
