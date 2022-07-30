TEXFILES=11-oscilaciones-arik.tex
PDFFILES=11-oscilaciones-arik.pdf

all : ${PDFFILES}

clean :
	rm *aux *~ *.log *.dvi

08a-oszilazioak-arik.pdf : 11-oscilaciones-arik.tex\
			./Log_Vert2_B_N_media.pdf \
			./upvgraf.pdf ./ikasturtea.tex \
			./logoak/watermark.tex ./komandoak.tex
	pdflatex 11-oscilaciones-arik.pdf


