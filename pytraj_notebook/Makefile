build:
	amber.jupyter nbconvert --to html notebook.ipynb
	zip tutorial_files.zip notebook.* Makefile README.md images/* data/*
	cp notebook.html index.html
