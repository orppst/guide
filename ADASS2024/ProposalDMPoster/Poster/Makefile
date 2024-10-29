.PHONY: main clean FORCE

main: ProposalDMPoster.pdf

ProposalDMPoster.pdf: ProposalDMPoster.tex
	latexmk -pdflatex='lualatex -interaction nonstopmode' -pdf ProposalDMPoster.tex

clean:
	latexmk -pdf -C