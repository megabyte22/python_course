all: 01_numpy_scipy.pdf 02_matplotlib.pdf 03_pandas.pdf 04_seaborn.pdf

01_numpy_scipy.pdf: 01_numpy_scipy.tex
	latexmk -pdf 01_numpy_scipy.tex

02_matplotlib.pdf: 02_matplotlib.tex
	latexmk -pdf 02_matplotlib.tex

03_pandas.pdf: 03_pandas.tex
	latexmk -pdf 03_pandas.tex

04_seaborn.pdf: 04_seaborn.tex
	latexmk -pdf 04_seaborn.tex

.PHONY: clean

clean:
		latexmk -c
		rm -rf *.pdf
		rm -rf *.vrb
		rm -rf *.snm
		rm -rf *.nav
