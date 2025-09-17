## O que instalar

Compilador LaTeX → para gerar o PDF do TCC.

MiKTeX (Windows)
Precisa do Perl
Rodar no terminal:
latexmk -pdf main.tex

Como compilar manualmente (caso n baixe o pearl):
pdflatex main.tex
bibtex main      # só se tiver bibliografia
pdflatex main.tex
pdflatex main.tex

Vai gerar o PDF final main.pdf.
