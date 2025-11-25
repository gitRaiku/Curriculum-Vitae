all: ../PintilieSebastianCV.pdf

.PHONY: CV

../PintilieSebastianCV.pdf: cv.tex
	pdflatex cv.tex
	mv cv.pdf ../PintilieSebastianCV.pdf

run: ../PintilieSebastianCV.pdf
	sioyek ../PintilieSebastianCV.pdf

clean:
	rm -f cv.log cv.out cv.aux
