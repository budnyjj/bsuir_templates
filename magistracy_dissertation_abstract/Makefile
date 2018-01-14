default: compile

compile:
	pdflatex dissertation.tex

bib:
	bibtex8 -B dissertation.aux

clean:
	$(RM) *.log
	$(RM) *~
	$(RM) *.dvi
	$(RM) text/*.log
	$(RM) text/*~
	$(RM) text/*.dvi


.PHONY: clean compile

