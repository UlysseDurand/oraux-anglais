SHELL := /bin/bash

compile:
	python3 compile.py custom.lgi ../fiche.txt latex -o fiche.tex
	pdflatex *.tex
	cp *.pdf ../
