all:
	{ \
	rm "Introduction to Variability Mechanisms in Java".pdf ;\
	latexmk -pdf -shell-escape main.tex ;\
	mv main.pdf "Introduction to Variability Mechanisms in Java".pdf ;\
	latexmk -CA ;\
	rm -R _minted-main ;\
	rm main.bbl ;\
	evince "Introduction to Variability Mechanisms in Java".pdf ;\
	}
