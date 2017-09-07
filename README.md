LuaLaTeX package luabibentry v0.1a, 2012-02-02.
Copyright (c) Oliver Kopp, 2012

Summary
-------
luabibentry is a reimplementation of bibentry.sty by Patrick W. Daly.
It provides the command \bibentry{<BibTeXKey>} to print the 
bibliographic entry in the main document.


Generating the package
----------------------
To produce the package and the manual from `luabibentry.dtx' you have to run

    tex luaindex.dtx
and pdflatex luaindex.dtx

or make all


Installation
------------
Distributors should save 
  luabibentry.lua as TDS:luatex/luabibentry/luabibentry.lua and
  luabibentry.sty as TDS:luatex/luabibentry/luabibindex.sty.

A TDS-friendly .zip can be obtained by "make tds"


License
-------
This file is part of the LuaLaTex package `luabibentry'.
 
This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, version 1.3c of the license.
The latest version of this license is in
  http://www.latex-project.org/lppl.txt
and version 1.3c or later is part of all distributions of LaTeX 
version 2005/12/01 or later.

This work has the LPPL maintenance status "maintained".

The Current Maintainer and author of this work is Oliver Kopp.

This work consists of the files `luabibentry.dtx' and `README'.
