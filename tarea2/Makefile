DOC = similaridad

pdf: $(DOC).pdf
dvi: $(DOC).dvi

%.dvi: %.tex
	latex $^
	latex $^

%.pdf: %.tex
	pdflatex $^
	pdflatex $^

clean:
	rm *.aux *.log *.dvi *.pdf *.tex~
