all: similaridad.dvi
pdf: similaridad.pdf

%.dvi: %.tex
	latex $^

%.pdf: %.tex
	pdflatex $^

clean:
	rm *.aux *.log *.dvi *.pdf
