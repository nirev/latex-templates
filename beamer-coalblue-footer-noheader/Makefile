TITLE=app

all:
	pdflatex $(TITLE).tex
	pdflatex $(TITLE).tex
	
bibtex:
	latex $(TITLE).tex
	bibtex $(TITLE)

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.tex~ *.toc *.bbl *.blg
