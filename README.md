# Biología de Recursos Pesqueros — Bookdown

**Prof. Luis Cubillos | Universidad de Concepción | 2025–2026**

Apuntes y guías de estudio de la asignatura Biología de Recursos Pesqueros, publicados como libro web interactivo con [bookdown](https://bookdown.org/). El libro se construye semana a semana a medida que avanza el curso.

## 🌐 Ver el libro

> https://luisacubillos.github.io/BiolRec_Book/

## 📚 Contenidos

| Capítulo | Tema | Estado |
|---|---|---|
| Prefacio | Presentación del libro y cómo usarlo | ✅ |
| Clase 1 | Introducción a los Recursos Marinos | ✅ |
| Clase 2 | Recursos Acuáticos Renovables: Crustáceos Demersales | ✅ |
| Clase 3 | Dinámica poblacional — modelos de crecimiento y mortalidad | 🔜 |

## 📁 Estructura del repositorio

```
BiolRec_Book/
├── _bookdown.yml          # Configuración del libro (orden de capítulos)
├── _output.yml            # Formatos de salida (gitbook, pdf)
├── index.Rmd              # Portada y prefacio
├── 01-introduccion.Rmd    # Clase 1: Introducción a los Recursos Marinos
├── 02-crustaceos.Rmd      # Clase 2: Crustáceos Demersales
├── estilos/book.css       # Hoja de estilos
├── referencias.bib        # Bibliografía BibTeX
└── .github/workflows/     # GitHub Actions (publicación automática)
```

## 🚀 Compilar localmente

```r
# Instalar dependencias si aún no están
install.packages(c("bookdown","ggplot2","dplyr","tidyr","scales","kableExtra"))

# Compilar el libro completo
bookdown::render_book("index.Rmd")
```

El libro se genera en la carpeta `_book/`. Ábrelo con `_book/index.html`.

## 📦 Dependencias R

- `bookdown`, `rmarkdown`, `knitr`
- `ggplot2`, `dplyr`, `tidyr`, `scales`
- `kableExtra`

## 🔄 Publicación automática

Cada `push` a la rama `main` activa un GitHub Action que compila el libro y lo publica en GitHub Pages (rama `gh-pages`). El proceso toma aproximadamente 5 minutos.

## 📄 Licencia

Material de uso docente — Universidad de Concepción. Prohibida su reproducción con fines comerciales sin autorización del autor.
