# Introduction to Probability
A copy of the source for Grinstead and Snell's lovely probability book

I have simply copied the original source here and modified it slightly
to be easier to build using modern TexLive distributions.

To produce a pdf of the book:

```
cd src/main/latex
pdflatex prob.tex 
pdflatex prob.tex 
```
You have to run pdflatex twice so that it can stabilize all references
to figures and such.

If you get new postscript versions of the figures, you can convert
them all to pdf using the `convert_ps` script thusly:

```
src/main/sh/convert_ps
```

# Programs
The directory layout that I have here is intended to make it easier to
put programs in various languages next to the book for reference. In
particular, it seems like a good idea to convert the original BASIC
programs to a more widely used language like R or python.
