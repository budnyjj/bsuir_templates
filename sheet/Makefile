default: bib compile

compile:
	pdflatex sheet.tex

bib: compile
	bibtex8 -B sheet.aux

clean:
	$(RM) *.log
	$(RM) *~
	$(RM) *.dvi
	$(RM) text/*.log
	$(RM) text/*~
	$(RM) text/*.dvi

.PHONY: clean compile

