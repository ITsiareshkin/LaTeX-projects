latex: proj4.tex
	latex proj4.tex
	bibtex proj4.aux
	latex proj4.tex
	latex proj4.tex
	dvips proj4.dvi
	ps2pdf -sPAPERSIZE=a4 proj4.ps

vlna: proj4.tex
	vlna -l -m -n proj4.tex

clean:
	rm proj4.aux proj4.log proj4.dvi proj4.ps proj4.bbl proj4.blg proj4.out
