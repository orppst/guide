.PHONY: main clean FORCE

main: ProposalDMPoster.pdf ProposalDMPoster.jpg

ProposalDMPoster.pdf: ProposalDMPoster.tex
	latexmk -pdflatex='lualatex -interaction nonstopmode' -pdf $<

ProposalDMPoster.jpg: ProposalDMPoster.pdf
	pdftoppm -jpeg -scale-to-x 2160 -scale-to-y 3840 -singlefile  $<  > $@

clean:
	latexmk -pdf -C