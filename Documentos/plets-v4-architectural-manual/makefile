all:
	{ \
	rm "plets-v4-architectural-manual".pdf ;\
	latexmk -pdf -shell-escape main.tex ;\
	mv main.pdf "plets-v4-architectural-manual".pdf ;\
	latexmk -CA ;\
	rm -R _minted-main ;\
	rm main.bbl ;\
	evince "plets-v4-architectural-manual".pdf ;\
	}
