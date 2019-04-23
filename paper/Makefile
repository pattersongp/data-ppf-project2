paper:
	pdflatex $@.tex && bibtex $@.aux && pdflatex $@.tex

.PHONY : clean
clean :
	rm -f *.log *.aux *.out *.pdf *.bbl *.blg
