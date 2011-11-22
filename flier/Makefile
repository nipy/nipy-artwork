all: pics nipy-handout.pdf eppy-handout.pdf
#	rst2pdf materials.rst

pics:
	$(MAKE) -C ../pics psychopy_logo.pdf opensesame_logo.pdf snakebrain.pdf
	$(MAKE) -C ../pics

%-handout.pdf: %-handout.tex common-handout.tex
	pdflatex $<

nipy-handout.tex: materials.rst
	rst2latex $< | sed -e 's/\.svg/.pdf/g' >| $@
