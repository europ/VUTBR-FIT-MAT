FILE=3_termin_D_2018-2019


.PHONY: make
make: clean
	@pdflatex $(FILE)


.PHONY: clean
clean:
	@rm -fv *.aux *.log *.dvi *.ps *.bbl *.blg *.toc *.out *.lof


.PHONY: clean-all
clean-all: clean
	@rm -fv *.pdf
