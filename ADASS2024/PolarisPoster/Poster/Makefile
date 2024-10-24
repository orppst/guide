.PHONY: main clean FORCE

main: poster.pdf

poster.pdf: FORCE
	latexmk -pdflatex='lualatex -interaction nonstopmode' -pdf PolarisPoster_beamer.tex

clean:
	latexmk -pdf -C