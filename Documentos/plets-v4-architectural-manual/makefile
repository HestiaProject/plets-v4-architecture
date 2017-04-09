all:
	{ \
	rm "autorest_report_laser_dumer".pdf ;\
	latexmk -pdf -shell-escape principal.tex ;\
	mv principal.pdf "autorest_report_laser_dumer".pdf ;\
	latexmk -CA ;\
	rm -R _minted-principal ;\
	rm principal.bbl ;\
	rm principal.glo ;\
	rm principal.ist ;\
	rm principal.glg ;\
	rm principal.gls ;\
	rm principal.alg ;\
	rm principal.acr ;\
	rm principal.acn ;\
	evince "autorest_report_laser_dumer".pdf ;\
	}
