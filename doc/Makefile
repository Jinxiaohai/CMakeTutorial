EXE=doc.pdf
SRC=doc.tex
BIB=doc.aux

$(EXE):$(SRC)      ;    xelatex $(SRC)

.PHONY.:look
look:              ;    evince doc.pdf

.PHONY.:clean
clean:             ;    $(RM) doc.aux doc.log doc.pdf doc.dvi doc.bbl doc.blg doc.toc doc.out doc.nav doc.snm doc.thm doc.lot doc.lof
