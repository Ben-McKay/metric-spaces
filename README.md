Lecture notes on metric spaces for undergraduate students of mathematics. 
The main output file is metric-space-notes.pdf. 
The main input file is metric-space-notes.tex.
This is a book in LaTeX 2e. 
To compile the file, you need to use the following command line commands in Linux:
pdflatex --shell-escape -synctex=1  -recorder metric-space-notes.tex
bibtex metric-space-notes 
makeindex -s notation.gst -o not.gls not.glo  
makeindex metric-space-notes
and repeat each of these many times.
