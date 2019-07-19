
all: main.pdf clean
	atril -i 1 main.pdf

%.pdf: %.tex
	pdflatex $<

clean:
	-rm -f *.aux
	-rm -f *.log
	-rm -f *.nav
	-rm -f *.out
	-rm -f *.snm
	-rm -f *.toc
	-rm -f *.vrb

realclean: clean
	-rm -f *.pdf

