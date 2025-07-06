Master thesis by Li Zhang 
====================================================================================== 
**Do not redistribute, copy, or reuse any part of this content without permission.**

# Source:
This repository includes my master-thesis by Latex based on an existing Latex template: https://github.com/cyrraz/phd-thesis developed by Cyrille Praz ([@cyrraz](https://github.com/cyrraz)).

# Note:
- Add **latex-workshop.latex.recipe.default": "latexmk (xelatex)** in the settings.json file at .vscode directory for compiling some japanese characters in this thesis.
    ```
    {
    "latex-workshop.latex.recipe.default": "latexmk (xelatex)"
    }
    ```

- Sometimes files or directories are zipped due to disk limitation. Unzip them before compiling.

The main files and folders are:
* `master_thesis.tex`: main tex file whose purpose is to import all the other tex files;
* `Makefile`: makefile to produce the pdf of the thesis;
* `figs.zip`: folder containing the figures;
* `tables.zip`: folder containing the tables;
* `chapters/`: folder containing the tex files of the thesis chapters and appendices;
* `include/packages.tex`: file listing the used packages;
* `include/styles.tex`: file defining the style of the thesis;
* `include/definitions.tex`: file defining new commands/shortcuts;
* `include/glossary.tex`: file defining acronyms for the glossary;
* `include/bibliography.bib`: file containing BibTeX entries, which can be maintained with [JabRef](https://www.jabref.org/);
* `include/jhep.bst`: BibTeX style file;
* `include/belle2sym.tex`: file defining particle symbols.

# Comments:
