TARGET=paper

$(TARGET):
	pdflatex $@.tex && bibtex $@.aux && pdflatex $@.tex

.PHONY : open
open:
	open $(TARGET).pdf

.PHONY : all
all: clean $(TARGET) open

.PHONY : clean
clean :
	rm -f *.log *.aux *.out *.pdf *.bbl *.blg
