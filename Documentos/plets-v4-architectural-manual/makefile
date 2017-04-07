all:
	{ \
	rm "plets-v4-architectural-manual".pdf ;\
	latexmk -pdf -shell-escape main.tex ;\
	mv main.pdf "plets-v4-architectural-manual".pdf ;\
	latexmk -CA ;\
	rm -R _minted-main ;\
	rm main.bbl ;\
	rm main.glo ;\
	rm main.ist ;\
	rm main.glg ;\
	rm main.gls ;\
	evince "plets-v4-architectural-manual".pdf ;\
	}
