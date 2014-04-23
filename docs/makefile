all:
	latex presen11.tex
	latex presen11.tex
#	bibtex presen11
#	latex presen11.tex
#	latex presen11.tex
	dvips -o presen11.ps presen11.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true presen11.ps presen11.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl *.*~ tex/*.*~
