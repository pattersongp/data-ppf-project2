paper:
	pdflatex $@.tex && bibtex $@.aux && pdflatex $@.tex && open $@.pdf

.PHONY : clean
clean :
	rm -f *.log *.aux *.out *.pdf *.bbl *.blg
