

main.pdf: main.tex
	pdflatex $<

clean:
	ls main.* | grep -v tex | xargs rm -f 
	rm -f *.aux
