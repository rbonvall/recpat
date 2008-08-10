DOC = similaridad

pdf: $(DOC).pdf
dvi: $(DOC).dvi

%.dvi: %.tex
	latex $^

%.pdf: %.tex
	pdflatex $^

clean:
	rm *.aux *.log *.dvi *.pdf *.tex~
