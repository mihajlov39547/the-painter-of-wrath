# The Painter of Wrath (LaTeX)

This workspace is set up to write a 19-chapter book in LaTeX.

## Structure

- `main.tex` — entrypoint (includes frontmatter, 19 chapters, backmatter)
- `frontmatter/` — title + other front sections
- `chapters/` — `chap01.tex` … `chap19.tex`
- `backmatter/` — end matter (currently `notes.tex`)

## Build a PDF

If you have a LaTeX distribution installed (MiKTeX or TeX Live), from this folder run:

```powershell
pdflatex main.tex
pdflatex main.tex
```

This produces `main.pdf`.

## (Later) Convert to EPUB

A common approach is using Pandoc to convert LaTeX → EPUB:

```powershell
pandoc main.tex -o The-Painter-of-Wrath.epub
```

Notes:
- EPUB conversion quality depends on how complex your LaTeX is.
- If you add lots of custom LaTeX, you may need to tweak the Pandoc command or switch to a LaTeX-to-HTML workflow first.

## Writing

Start writing inside `chapters/chap01.tex` (and onward). Update chapter titles by editing the `\chapter{...}` line in each file.
