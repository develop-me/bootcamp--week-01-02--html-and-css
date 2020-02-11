# the template files
templates := $(shell find ../../latex-templates -type f -name "*.tex" -depth 1)

# the tex files in this directory (and any below)
tex := $(shell find . -type f -name "*.tex")

# the resources (js, php, eps, etc.)
# source := $(shell find ./resources -type f)

# build notes.pdf whenever any of the above have changed
# make sure to use a tab (not spaces) for the commands below
html.pdf: $(templates) $(tex) $(source)
	# build using xelatex
	xelatex --halt-on-error --shell-escape html.tex

	# open preview in the background
	open -g html.pdf
