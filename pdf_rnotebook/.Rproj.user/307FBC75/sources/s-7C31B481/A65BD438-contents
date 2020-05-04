Demo for making pdf document
========================================================
author: Asela Wijeratne
date: 5/04/2020
autosize: true

Reference and more information 
========================================================

R Markdown: The Definitive Guide

Yihui Xie, J. J. Allaire, Garrett Grolemund

2020-04-26


Installations
========================================================
- For PDF outputs: install LaTeX 
- If you don't have LaTeX before, install TinyTeX

```
install.packages('tinytex')
tinytex::install_tinytex()  # install TinyTeX
```

Table of contents
========================================================
- Add a table of contents using the ```toc``` option 
- Specify the depth of headers  the ```toc_depth```

```
---
title: "Habits"
output:
  pdf_document:
    toc: true
    toc_depth: 2
---
```

Figure options
========================================================
- `fig_width` and `fig_height` can be used to control the default figure width and height
- fig_caption controls whether figures are rendered with captions 


```
---
title: "Habits"
output:
  pdf_document:
    fig_width: 7
    fig_height: 6
    fig_caption: true
---
```

Data frame printing
========================================================
- You can enhance the default display of data frames via the `df_print`

```
---
title: "Habits"
output:
  pdf_document:
    df_print: kable
---
```
LaTeX options
========================================================
- Customize LaTeX template using top-level YAML metadata

```
---
title: "Crop Analysis Q3 2013"
output: pdf_document
fontsize: 11pt

---
```
LaTeX packages for citations
========================================================
- PDF output, recommended LaTeX packages

-- natbib

-- biblatex

```
---
output:
  pdf_document:
    citation_package: natbib
---
```

