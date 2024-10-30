.PHONY: main clean FORCE

main: PolarisPoster.pdf

PolarisPoster.pdf: FORCE
	latexmk -pdflatex='lualatex -interaction nonstopmode' -pdf PolarisPoster.tex

clean:
	latexmk -pdf -C