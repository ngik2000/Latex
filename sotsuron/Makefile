TARGET	= syuron
TEX	= tex/*.tex
IMAGE	= image/*.pdf

syuron.pdf: syuron.dvi
	dvipdfmx $(TARGET).dvi

syuron.dvi: syuron.tex $(TEX) $(IMAGE)
	platex -interaction=batchmode $(TARGET).tex
	platex -interaction=batchmode $(TARGET).tex
