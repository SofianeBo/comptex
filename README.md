# comptex

This is a compiler for latex documents. It significantly simplifies the process of PDF and avoids compilation/referencing errors. Flag it as executable and add its parent folder to the $PATH of your shell.

USAGE:   comptex [-options] file[.tex]
OPTIONS: 
	-B 	: do NOT invoke bibtex
	-c	: clean directory after compilation
	-a	: keep .aux file after compilation (if -c is invoked)
	-b	: keep .bbl file after compilation (if -c is invoked)
	-C	: clean only	
	-S	: show PDF
	-l	: latex instead of pdflatex
	-x  : xelatex instead of pdflatex
	-g <lib>  : update <lib> with new cite references.
	-G <lib>  : update <lib> only.
  
  
  I typically use "comptex -cS" to compile my tex files.  

  Creation: 2010.
