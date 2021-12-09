# Starting with a New Project

### Code:
\documentclass{article}  

\begin{document}  
First document. This is a simple example, with no extra parameters or packages included.  
\end{document}  

***Note:*** The input file is just a plain text file, with the extension ".tex"

The part of your ".tex" file before this point is called the preamble. In the preamble, you define the type of document you are writing and the language, load extra packages you will need, and set several parameters. 

Ex1: \documentclass[12pt, letterpaper]{article}   
=> The extra parameters set the font size (12pt) and the paper size (letterpaper).  
Ex2: \usepackage[utf8]{inputenc}  
=> This is the encoding for the document, to allow characters beyond ASCII (e.g. à, ü, č ...) to be used in the text.  
Ex3: \title{First document} \author{Abc} \date{February 2016}  
=> These lines are self-descriptive as this part is used to display the title, author and date when the document was written.   
