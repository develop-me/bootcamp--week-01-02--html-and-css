# the template files
templates := $(shell find ../../latex-templates -type f -name "*.tex" -depth 1)

# the tex files in this directory (and any below)
tex := $(shell find . -type f -name "*.tex")

# the resources (js, php, eps, etc.)
# source := $(shell find ./resources -type f)

all: html.pdf css.pdf web-theory.pdf

# build notes.pdf whenever any of the above have changed
# make sure to use a tab (not spaces) for the commands below
html.pdf: $(templates) $(tex) $(source)
	# build using xelatex
	xelatex -file-line-error --halt-on-error --shell-escape html.tex && xelatex --shell-escape html.tex

	# open preview in the background
	open -g html.pdf

web-theory.pdf: $(templates) $(tex) $(source)
	# build using xelatex
	xelatex -file-line-error --halt-on-error --shell-escape web-theory.tex && xelatex --shell-escape web-theory.tex

	# open preview in the background
	open -g web-theory.pdf

css.pdf: $(templates) $(tex) $(source)
	# build using xelatex
	xelatex -file-line-error --halt-on-error --shell-escape css.tex && xelatex --shell-escape css.tex

	# open preview in the background
	open -g css.pdf
