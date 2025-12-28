[![DOI](https://zenodo.org/badge/1124190613.svg)](https://doi.org/10.5281/zenodo.18076255)
[![GitHub release](https://img.shields.io/github/v/release/mihajlov39547/the-painter-of-wrath)](https://github.com/mihajlov39547/the-painter-of-wrath/releases/tag/v1.0)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)


# The Painter of Wrath (LaTeX Project)

**The Painter of Wrath** is a non-commercial, academic/critical literary adaptation and reinterpretation of *Deus Irae* (1976) by Philip K. Dick and Roger Zelazny.

This repository contains the complete LaTeX source for a rewritten, reframed, and expanded edition intended for study, critical engagement, and preservation. It is **not authorized**, **not monetized**, and **not offered for sale**. Its purpose is scholarly and literary, not commercial.

---

## About This Edition

This project does **not** seek to replace or supersede the original novel. Instead, it treats *Deus Irae* as a living text whose ideas—wrath, belief, institutional faith, and moral responsibility—can be re-engaged through transformation.

Key characteristics of this adaptation:

- Modernized cadence and language where appropriate
- Structural reframing for narrative continuity
- A newly written **Prologue**
- **Three Epilogues** exploring consequence rather than revelation
- An **archival artifact** suggesting institutional containment of doubt
- A concluding **Notes** section explaining intent and ambiguity

Readers are encouraged to seek out and read the original *Deus Irae* alongside this work.

---

## Repository Structure

```
.
├── main.tex                # Master document
├── frontmatter/            # Title page, copyright, etc.
│   ├── title.tex
│   └── copyright.tex
├── chapters/               # Prologue + Chapters 1–19
│   ├── prologue.tex
│   ├── chap01.tex
│   ├── ...
│   └── chap19.tex
├── backmatter/             # Epilogues, Notes, Back Cover
│   ├── epilogues.tex
│   ├── epilogue1.tex
│   ├── artifact.tex
│   ├── epilogue2.tex
│   ├── epilogue3.tex
│   ├── notes.tex
│   └── backcover.tex
└── README.md               # This file
```

---

## Building the PDF

You will need a LaTeX distribution such as **TeX Live** or **MiKTeX**.

From the project root, run:

```bash
pdflatex main.tex
pdflatex main.tex
```

Running it twice ensures the table of contents and references are correct.

Note: The manuscript files use LaTeX-safe punctuation (e.g., ``quotes'' and `---` dashes) so they compile cleanly with `pdflatex`.

The output will be:

```
main.pdf
```

---

## Optional: EPUB Conversion

You may convert the project to EPUB for **personal, non-commercial use** using Pandoc:

```bash
pandoc main.tex -o The-Painter-of-Wrath.epub
```

Notes:
- Conversion quality depends on LaTeX complexity.
- Minor formatting adjustments may be required for best results.
- The EPUB must remain **free** and clearly labeled as a critical adaptation.

---

## License & Use

See [LICENCE](LICENCE) for the full licensing and attribution terms.

- This project is shared freely.
- No commercial use is permitted.
- No distribution of modified material is permitted.
- No claim of ownership over the original text or characters is made.
- All rights to *Deus Irae* remain with the respective rights holders.

This adaptation exists in the spirit of:
- literary preservation
- scholarly dialogue
- homage to Philip K. Dick and Roger Zelazny

---

## Authorship of This Adaptation

**The Painter of Wrath**  
Rewritten, reframed, and expanded by **Marko Mihajlović**  
Non-commercial academic/critical edition

---

## Citation

GitHub uses [CITATION.cff](CITATION.cff). Suggested citation:

Mihajlović, Marko. *The Painter of Wrath*. Rewritten, reframed, and expanded
non-commercial critical adaptation of *Deus Irae* by Philip K. Dick and
Roger Zelazny. 2025.

BibTeX:

```bibtex
@book{mihajlovic2025painter_of_wrath,
	title     = {The Painter of Wrath: A Non-Commercial Critical Adaptation of Philip K. Dick and Roger Zelazny's Deus Irae},
	author    = {Mihajlović, Marko},
	year      = {2025},
	note      = {Rewritten, reframed, and expanded critical adaptation},
}
```

---

## Final Note

> A face can become law.  
> A story can become a prison.  
> But a question---properly asked---can still open a door.

