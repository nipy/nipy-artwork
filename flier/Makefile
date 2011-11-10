all: pics
	rst2pdf materials.rst

pics:
	$(MAKE) -C ../pics psychopy_logo.pdf opensesame_logo.pdf
	$(MAKE) -C ../pics

%.pdf: %.tex
	pdflatex $<

nipy-handout.tex: materials.rst
	rst2latex $< | sed -e 's/\.svg/.pdf/g' >| $@
