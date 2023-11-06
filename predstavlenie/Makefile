LTXARGS = -pdf -lualatex -use-make -interaction=nonstopmode

%.tex: .FORCE
	latexmk $(LTXARGS) $(notdir $@)

.FORCE:
