all: envdraw.ps envdraw.dvi

envdraw.dvi: envdraw.tex
	latex envdraw.tex

envdraw.ps: envdraw.dvi
	dvips envdraw.dvi -o envdraw.ps

semiclean:
	rm -f *.aux *.fn *.log *.ky *.pg *.toc *.tp *.vr *.cp *.fns

clean: semiclean
	rm -f *.info *.dvi *.html *.gz
