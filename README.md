# CMU Statistics & Data Science Thesis Template

This LaTeX template is designed for Ph.D. students in the [Department of
Statistics & Data
Science](https://www.cmu.edu/dietrich/statistics-datascience/index.html) at
Carnegie Mellon University. It was created by Alex Reinhart based on a template
by Heidi Sestrich, itself based on a template from the University of Tennessee,
Knoxville.

To use this template, you can either:

- Make a copy of this repository under your own GitHub account by pressing the
  green "Use this template" button. Then you can clone the repository to your
  computer and work in it like any other Git repository.
- In the Releases section on the GitHub page for this template, download a Zip
  file containing the template.

Once you have the template on your computer, decide which version to use:

- `thesis.tex` uses plain LaTeX. You can generate figures and tables separately,
  save them, and include them in the LaTeX like you'd include any other image or
  table.
- `thesis-knitr.Rnw` uses Knitr to allow you to embed R code directly in the
  LaTeX source (just like R Markdown lets you put R in Markdown). You can write
  R in your thesis files to generate figures, tables, and other results. RStudio
  knows how to edit Rnw files and compile them to PDF.

Once you've picked, open the file and follow the instructions inside.

## Thesis options

The first line of each file gives the options for the LaTeX documentclass.

```latex
\documentclass[draft]{cmustatthesis}
```

Options are separated by commas. Two are important:

- `draft`: Marks the thesis with a draft notice giving the date. This is useful
  so that if you share drafts with your advisor or committee as you revise, they
  know which version they're reviewing.
- `printing`: If you want a printed and bound copy of your thesis, use the
  `printing` option. This makes a PDF where colored links are disabled (since
  they don't print well), and ensures each new chapter starts on the right-hand
  side. Margins are also adjusted so the document will be easy to read when
  printed and bound.

## LaTeX tips

Compile the thesis document and review the first chapter, which gives tips on
formatting your thesis.

You may need a relatively recent installation of LaTeX to use the font options
provided, where "recent" means later than, say, 2018. If you don't remember when
you last installed LaTeX, it may be a good time to update your installation.
