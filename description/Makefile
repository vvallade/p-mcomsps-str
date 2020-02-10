description.pdf : description.tex biblio.bib
	pdflatex description.tex
	bibtex description 
	pdflatex description.tex
	pdflatex description.tex
	rm -f description.bbl description.blg description.brf description.out \
      description.log description.aux description.toc description.spl

clean :
	rm -f description.pdf description.bbl description.blg description.brf \
      description.out description.log description.aux	description.toc \
      description.spl
