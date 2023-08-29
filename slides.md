---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Welcome to Slidev
---

# Taller de latex

centro cultural de avanzada y tecnologica

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# The latex project

LaTeX is a high-quality typesetting system; it includes features designed for
the production of technical and scientific documentation. LaTeX is the de facto
standard for the communication and publication of scientific documents.
LaTeX is available as free software.

LaTeX is not a word processor! Instead, LaTeX encourages authors not to worry
too much about the appearance of their documents but to concentrate on getting
the right content. For example, consider this document:


```
Cartesian closed categories and the price of eggs
Jane Doe
September 1994

Hello world!
```

```tex
\documentclass{article}
\title{Cartesian closed categories and the price of eggs}
\author{Jane Doe}
\date{September 1994}
\begin{document}
   \maketitle
   Hello world!
\end{document}
```

Read more about [Latex](https://www.latex-project.org/)


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
layout: default
---

# LaTeX Features

* Typesetting journal articles, technical reports, books, and slide presentations.
* Control over large documents containing sectioning, cross-references, tables and figures.
* Typesetting of complex mathematical formulas.
* Advanced typesetting of mathematics with AMS-LaTeX.
* Automatic generation of bibliographies and indexes.
* Multi-lingual typesetting.
* Inclusion of artwork, and process or spot colour.
* Using PostScript or Metafont fonts.

<br>

```
LaTeX is not a "tag" language in the sense of HTML or XML, where tags are used to define
the structure and formatting of content in a document. Instead, LaTeX is a typesetting
system that uses commands and markup to define how a document should be formatted.
```

---
transition: slide-up

level: 2
---


```html
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <h1>Welcome to My Page</h1>
    <p>This is some text.</p>
    <img src="image.jpg" alt="An image">
</body>
</html>
```



```tex
\documentclass{article}
\title{My Document}
\author{John Doe}
\date{\today}

\begin{document}
\maketitle

\section{Introduction}
This is the introduction to my document.

\subsection{Background}
Some background information goes here.

\end{document}

```


---

# Getting latex

## overleaf

[overleaf](https://www.latex-project.org/)

## Texlive

[texlive](https://tug.org/texlive/)

---

# Basic syntax
