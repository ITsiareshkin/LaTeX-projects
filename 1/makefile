#
# Projekt: Hladká a smíšená sazba 
# Autor: Ivan Tsiareshkin (xtsiar00)
# Datum: 6.3.2023 
#

latex: proj1.tex
	latex proj1.tex
	latex proj1.tex
	dvips -t a4 proj1.dvi
	ps2pdf proj1.ps

vlna: proj1.tex
	vlna -l -m -n proj1.tex
clean:
	rm proj1.dvi proj1.ps proj1.aux proj1.log proj1.out
