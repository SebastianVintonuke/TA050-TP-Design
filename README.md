Para instalar dependencias ejecutar:

```
sudo apt install latexmk texlive-latex-extra texlive-lang-spanish texlive-fonts-extra texlive-bibtex-extra biber
```

Instalar `LaTeX Workshop` extension para Visual Studio Code

Para compilar usar el LaTeX ejecutar:

```
latexmk -pdf ./main.tex
```

Para compilar puml a pdf

```
sudo apt install plantuml graphviz
```

```
plantuml -tpdf src/img/**/*.puml
```