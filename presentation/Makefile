default: compile

compile:
	pdflatex presentation.tex

bib:
	bibtex8 -B presentation.aux

clean:
	$(RM) *.log
	$(RM) *~
	$(RM) *.dvi
	$(RM) text/*.log
	$(RM) text/*~
	$(RM) text/*.dvi


.PHONY: clean compile

