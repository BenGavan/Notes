all:
	latex main.tex
	#bibtex main
	#latex main.tex
	latex main.tex
	dvipdf main


open:
	latex main.tex
	#bibtex main
	#latex main.tex
	latex main.tex
	dvipdf main
	open main.pdf

#diff:
#	latexdiff main.tex > diff_raw.tex
#	cat diff_raw.tex | tr -d '\015' > diff.tex
#	latex diff.tex
#	bibtex diff
#	latex diff.tex
#	latex diff.tex
#	dvipdf diff
#	pdflatex diff.tex
#	pdflatex diff.tex

#backup:
#	tar cvfz ../backup.tar.gz *; mv ../backup.tar.gz .

clean:
	rm -f main.aux  main.bbl  main.blg  main.dvi  main.log  main.pdf




#	 ref 25
#
# 	look at a.3