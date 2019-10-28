supplement.pdf: supplement.dvi
	-dvipdfmx supplement.dvi
supplement.dvi: ./*.tex
	-platex supplement.tex

.PHONY: clean

clean:
	rm -rf *~
	rm -rf *aux
	rm -rf *log
	rm -rf *dvi
