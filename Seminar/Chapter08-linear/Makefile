svm.pdf: svm.dvi
	-dvipdfmx svm.dvi
svm.dvi: svm.tex tex/*.tex
	-platex svm.tex

.PHONY: clean

clean:
	rm -rf *~
	rm -rf *aux
	rm -rf *log
	rm -rf *dvi
