Source files for the anthology *A NIME Reader — Fifteen Years of New Interfaces for Musical Expression*, edited by [Alexander Refsum Jensenius](http://www.hf.uio.no/imv/english/people/aca/tenured/alexanje/index.html) (University of Oslo) and [Michael J. Lyons](www.michaellyons.xyz/) (Ritsumeikan University) and published by Springer in 2017.


## Bibliographic information

The files in this archive are from the preprint version of the book. You may cite this source or the original Springer publication:

- Citation: Jensenius, Alexander Refsum & Lyons, Michael J. (ed.) (2017). *A NIME Reader: Fifteen Years of New Interfaces for Musical Expression*. Springer.
- DOI: <https://doi.org/10.1007/978-3-319-47214-0>
- ISBN: 978-3-319-47213-3
- Online ISBN: 978-3-319-47214-0


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

## About the book

What is a musical instrument? What are the musical instruments of the future? This anthology presents thirty papers selected from the fifteen year long history of the International Conference on New Interfaces for Musical Expression (NIME). NIME is a leading music technology conference, and an important venue for researchers and artists to present and discuss their explorations of musical instruments and technologies. Each of the papers is followed by commentaries written by the original authors and by leading experts. The volume covers important developments in the field, including the earliest reports of instruments like the reacTable, Overtone Violin, Pebblebox, and Plank. There are also numerous papers presenting new development platforms and technologies, as well as critical reflections, theoretical analyses and artistic experiences. The anthology is intended for newcomers who want to get an overview of recent advances in music technology. The historical traces, meta-discussions and reflections will also be of interest for longtime NIME participants. The book thus serves both as a survey of influential past work and as a starting point for new and exciting future developments.