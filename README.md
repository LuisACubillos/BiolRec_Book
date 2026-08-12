# Biología de Recursos Pesqueros — Bookdown

**Prof. Luis Cubillos | Universidad de Concepción | 2025**

Apuntes y guías de estudio de la asignatura Biología de Recursos Pesqueros, publicados como libro web interactivo con [bookdown](https://bookdown.org/).

## 🌐 Ver el libro

> https://lucubillos.github.io/BiolRec_Book/

## 📁 Estructura del repositorio

```
BiolRec_Book/
├── _bookdown.yml          # Configuración del libro (orden de capítulos)
├── _output.yml            # Formatos de salida (gitbook, pdf)
├── index.Rmd              # Portada y prefacio
├── 01-introduccion.Rmd    # Clase 1: Introducción a los Recursos Marinos
├── datos/                 # Datos de desembarque SERNAPESCA
├── estilos/book.css       # Hoja de estilos
├── referencias.bib        # Bibliografía BibTeX
└── .github/workflows/     # GitHub Actions (publicación automática)
```

## 🚀 Compilar localmente

```r
# Instalar bookdown si aún no está
install.packages("bookdown")

# Compilar el libro
bookdown::render_book("index.Rmd")
```

El libro se genera en la carpeta `_book/`.

## 📦 Dependencias R

- `bookdown`, `rmarkdown`, `knitr`
- `ggplot2`, `dplyr`, `tidyr`, `scales`
- `kableExtra`

## 📄 Licencia

Material de uso docente — Universidad de Concepción.
