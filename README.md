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

Once you have the template on your computer, open `thesis.tex` and follow the
instructions inside.

## Thesis options

The first line of `thesis.tex` gives the options for the class.

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
