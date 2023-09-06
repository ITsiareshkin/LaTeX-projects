#
# Projekt: Sazba dokumentů a matematických výrazů
# Autor: Ivan Tsiareshkin (xtsiar00)
# Datum: 20.3.2023 
#

latex: proj2.tex
	latex proj2.tex
	latex proj2.tex
	dvips -t a4 proj2.dvi
	ps2pdf proj2.ps

vlna: proj2.tex
	vlna -l -m -n proj2.tex

clean:
	rm proj2.dvi proj2.ps proj2.aux proj2.log proj2.out
