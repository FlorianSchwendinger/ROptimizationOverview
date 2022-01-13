file=Optimization

all: Optimization

Optimization:
	R -e 'rmarkdown::render("$(file).Rmd", clean = FALSE)'
	mv Optimization.knit.md Optimization.md

Taxonomy:
	R -e 'rmarkdown::render("Optimization_Taxonomy.Rmd", clean = FALSE)'
	mv Optimization_Taxonomy.knit.md Optimization_Taxonomy.md

clean:
	rm -f .Rhistory
	rm -f $(file).html $(file).log $(file).tex
