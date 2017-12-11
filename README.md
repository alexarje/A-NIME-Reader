# A-NIME-Reader

Source files for the anthology "A NIME Reader Fifteen Years of New Interfaces for Musical Expression", edited by [Alexander Refsum Jensenius](http://www.hf.uio.no/imv/english/people/aca/tenured/alexanje/index.html) (University of Oslo) and [Michael J. Lyons](www.michaellyons.xyz/) (Ritsumeikan University)


## Bibliographic information

The files in this archive are from the preprint version of the book *A NIME Reader — Fifteen Years of NewInterfaces for Musical Expression*, published by Springer. The following is the bibliographic information for the Springer publication:

-   DOI: <https://doi.org/10.1007/978-3-319-47214-0>
-   ISBN 978-3-319-47213-3
-   Online ISBN 978-3-319-47214-0


## Compile from source

The manuscript is written in LaTex. There is a makefile in the latex directory, so you should be able to type the following two commands in a terminal and get a complete PDF file: 

    cd latex
    make

If that does not work, you may run the latex and bibtex compile yourself. Then you would need to do the following four commands to get everything in place correctly: 

    pdflatex main
    bibtex main
    pdflatex main
    pdflatex main


## Fixing errors

One of the points of making these source files available, is to fix errors in the book. We are not going to make any big edits of the content, but will be happy to fix typos, broken URLs, etc. Please send us any errors your find, or branch and fix yourself. Thanks!