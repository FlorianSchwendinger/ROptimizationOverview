
all: render_all move

render_all:
	R -e "rmarkdown::render_site()"

move:
	cp -rf _site/* ../docs/
