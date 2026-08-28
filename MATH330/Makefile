MAIN = main
BUILD_DIR = .

.PHONY: all watch clean

all:
	latexmk -pdf $(MAIN).tex

watch:
	latexmk -pvc -pdf $(MAIN).tex

clean:
	latexmk -c
	rm -f *.aux *.log *.out *.toc *.fdb_latexmk *.fls *.synctex.gz *.tcb
