FOOTBRIDGE HSI PAPER STARTER
==============================

Files
-----
main.tex        Main Elsevier manuscript.
references.bib  BibTeX database.
figures/        Place manuscript figures here.

Class file
----------
You do NOT normally need to include a separate elsarticle.cls file.
The line

    \documentclass[preprint,a4paper,12pt]{elsarticle}

uses the elsarticle class installed with your LaTeX distribution
(e.g. TeX Live / MiKTeX / Overleaf).

Only include elsarticle.cls locally if:
1. your LaTeX installation does not provide it, or
2. a journal explicitly supplies a modified/custom version.

Compilation
-----------
Typical local sequence:

    pdflatex main
    bibtex main
    pdflatex main
    pdflatex main

Overleaf will normally handle this automatically.

Notes
-----
- The current structure follows the paper narrative developed in the chat.
- Percentile p is intentionally kept general in Section 4.1.
- The final percentile/correction is introduced only in the optimisation section.
- Replace placeholder title/authors/journal details as needed.
