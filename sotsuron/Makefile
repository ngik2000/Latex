TARGET	= sotsuron_nagaike
TEX	= tex/*.tex
IMAGE	= image/*.pdf

sotsuron_nagaike.pdf: sotsuron_nagaike.dvi
	dvipdfmx $(TARGET).dvi

sotsuron_nagaike.dvi: sotsuron_nagaike.tex $(TEX) $(IMAGE)
	platex -interaction=batchmode $(TARGET).tex
	platex -interaction=batchmode $(TARGET).tex
