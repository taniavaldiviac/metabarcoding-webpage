# Curso: Metabarcoding de comunidades de eucariontes

Sitio del curso construido con **Quarto** y publicado con **GitHub Pages**.

## uso rápido
1. Instala [Quarto](https://quarto.org) y R/RStudio.
2. Clona este repositorio.
3. Renderiza localmente:
   ```bash
   quarto render
   quarto preview
   ```
4. Publicación en GitHub Pages:
   - Activa Pages con la rama `gh-pages` (Actions la creará).
   - Revisa el *workflow* de Actions en `.github/workflows/quarto-publish.yml`.

## paquetes sugeridos
`tidyverse`, `ShortRead`, `Biostrings`, `dada2`, `phyloseq`, `vegan`, `ggplot2`, `patchwork`, `knitr`.

## estructura
- `_quarto.yml` configuración del sitio
- `index.qmd` portada
- `syllabus.qmd` programa y calendario
- `lectures.qmd` enlaces a diapositivas
- `labs.qmd` cuadernos de práctica
- `homework.qmd` tareas
- `final_project.qmd` instrucciones del proyecto
- `slides/` diapositivas revealjs
- `data/` datos de ejemplo (vacío)

---

> Basado conceptualmente en sitios de cursos académicos (p. ej., QERM 514 de UW). Este repositorio es un esqueleto que puedes adaptar libremente.
