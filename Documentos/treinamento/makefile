all:
	{ \
	rm "treinamento".pdf ;\
	latexmk -pdf -shell-escape main.tex ;\
	mv main.pdf "treinamento".pdf ;\
	latexmk -CA ;\
	rm -R _minted-main ;\
	rm main.bbl ;\
	rm main.glo ;\
	rm main.ist ;\
	rm main.glg ;\
	rm main.gls ;\
	rm main.alg ;\
	rm main.acr ;\
	rm main.acn ;\
	evince "treinamento".pdf ;\
	}
