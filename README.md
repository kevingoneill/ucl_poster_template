A simple poster template to comply with [UCL's branding scheme](https://www.ucl.ac.uk/brand/brand-essentials). Alternative color palettes are available via the package options, e.g. `\usepackage[purple]{ucl}`. Currently available options are `blue`, `green`, `pink`, `purple`, and `yellow`. For custom colorways, feel free to edit the color style code in `ucl.sty`.

The template is set up to use `biblatex` for citation. To use it, place BibTeX-formatted reference information in `references.bib`. Then, simply use `\parencite{articleName}` for parenthetical citations (i.e., "(Fleming, 2024)"), `\textcite{articleName}` for in-text citations (i.e., "Fleming (2024)"), or `\citeauthor{articleName}` or `\citeyear{articleName}` to cite just the author or year. The bibliography is printed using `\printbibliography`, with `\bibfont` controlling the bibliography font.

For more information on using LaTeX/Overleaf, see [this guide](https://www.overleaf.com/learn).

For information on the LaTeX class this package is built on, see [the `tikzposter` documentation](https://ctan.org/pkg/tikzposter).

Finally, for information about drawing in LaTeX, see [Overleaf's guide to TikZ](https://www.overleaf.com/learn/latex/TikZ_package).