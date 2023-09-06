latex: proj3.tex
	latex proj3.tex
	latex proj3.tex
	dvips proj3.dvi
	ps2pdf -sPAPERSIZE=a4 proj3.ps

vlna: proj3.tex
	vlna -l -m -n proj3.tex
clean:
	rm proj3.dvi proj3.ps proj3.aux proj3.log
