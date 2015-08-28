# Davis-dissertation-template

A template for a Markdown/Pandoc template for a UC Davis PhD dissertation or Masters' thesis.  Unlike other templates I've seen, this one should not require any dependencies beyond a typical TeX installation plus Pandoc, and it does not require any TeX commands at the command line.  Apart from a few TeX formatting commands inside the .md file, you should be able to write everything in pure Markdown.

On my machine, you can compile the template to a complete PDF file with the following pandoc command:

`pandoc -o dissertation.pdf --bibliography=bib.bib --csl=citation-style.csl -V geometry:margin=1in -V linestretch=2 -V fontsize=12pt dissertation.md`

Feel free to use the template for any purpose, but I cannot provide any support for it.  Also, although [my dissertation](https://github.com/davharris/dissertation) did pass inspection using this template, I cannot guarantee that it will meet all of the requirements for you (especially because Grad Studies could change the requirements in the future)

All of the fields in `dissertation.md` that you need to fill in should be marked with {{double braces}}. You can see what the template looks like using `dissrtation.pdf`.
