# comptex

This is a compiler for latex documents. It significantly simplifies the process of PDF and avoids compilation/referencing errors. Flag it as executable and add its parent folder to the $PATH of your shell.

USAGE:   `comptex [-options] file[.tex]` <br/> 
```
	-B 	: do NOT invoke bibtex<br/>     
	-c	: clean directory after compilation<br/> 
	-a	: keep .aux file after compilation (if -c is invoked)<br/> 
	-b	: keep .bbl file after compilation (if -c is invoked)<br/> 
	-C	: clean only<br/> 
	-S	: show PDF<br/> 
	-l	: latex instead of pdflatex<br/> 
	-x  : xelatex instead of pdflatex<br/> 
	-g <lib>  : update <lib> with new cite references.<br/> 
	-G <lib>  : update <lib> only.<br/> 
```	
I typically use `comptex -cS` to compile my tex files. <br/>
Creation: 2010.
