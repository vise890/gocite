# gocite
Create a .bib for your .tex file automatically

# 1 - Scanning for KEYs
```latex
From: http://sites.stat.psu.edu/~surajit/present/bib.htm

\citet{KEY} Bester et al. (1998)
\citep{KEY} (Bester et al. 1998)

Multiple citations work within a single cite, for example
\citep{KEY1, KEY2, KEY3, KEY4, ...} (Bester et al. 1998; Garibaldi et al. 1997, 1998a,b; ...)
The lettering of the citations and references is done automatically.

You can use optional arguments to get text before and after the citation(s):
\citep[hereafter B98]{KEY} (Bester et al. 1998, hereafter B98)
\citep[e.g.,][]{KEY} (e.g., Bester et al. 1998)
\citep[see][p. 68]{KEY} (see Bester et al. 1998, p. 68)

Any of these can have a * affixed to make a full author list when "et al."
would normally be used, e.g.,
\citet*{KEY} Bester, Winters, & Alexander (1998)

Note that the nat2jour.pl script takes care of the bizarre practice of listing
three names on the first citation and using "et al." thereafter, so you don't
need to worry about that, although the intermediate file will come out "wrong".

\citeauthor{KEY} Bester et al.
\citeyear{KEY} 1998
\citeyearpar{KEY} (1998)

\citealp and \citealt are the sames as \citep and \citet, respectively, except
that they do not produce any parentheses at all:
\citealt{KEY} Bester et al. 1998

```
