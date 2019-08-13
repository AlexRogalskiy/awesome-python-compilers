Blogs
=====

* 2013-07-26 [The obvious Python parser](http://blog.nullspace.io/obvious-python-parser.html) -
  Constructing Python3 parser. In Haskell, d'oh. Code: https://github.com/hausdorff/pyli
* 2014-02-24 http://abecedarius.tumblr.com/post/77679122389/ouroborospy
* http://abecedarius.tumblr.com/post/79850464139/tail-eaten-well-almost
* 2016-10 [Dragon taming with Tailbiter, a bytecode compiler for Python](https://codewords.recurse.com/issues/seven/dragon-taming-with-tailbiter-a-bytecode-compiler) -


http://aosabook.org/en/500L/a-python-interpreter-written-in-python.html

Sites
=====

* HotPy
  * http://hotpy.blogspot.com/
  * https://sites.google.com/site/makingcpythonfast/
  * https://code.google.com/archive/p/hotpy/
  * https://bitbucket.org/markshannon/hotpy_2
* http://wildideas.org/basil/

Projects
========

* 1997-1999 [Python2C](https://web.archive.org/web/20011025084441/http://www.mudlib.org/~rassilon/p2c/)
* 1997-2000 PyFront (afterwards Basil)
* 1998-11 7th International Python Conference
  * From Jon Riehl's [notes](https://wildideas.org/basil/):
  > Last year (IPC7,) I thought I was going to surprise the Python community
  > by presenting a prototype Python to C translator. Little did I know,
  > I was only one of three people who announced such a product.
 * These apparently were:
   * "Converting Python Virtual Machine Code to C", John Aycock
   * "PyFront: Conversion of Python to C Extension Modules", Jon Riehl
   * (3rd - ???)
* 2000-01 8th International Python Conference
  * From Jon Riehl's [notes](https://wildideas.org/basil/):
  > This year (IPC8,) in the interest of keeping people up to date,
  > there was a two hour session that hosted the developers of these
  > prototypes. The only system left standing is now complete and under
  > beta test. Bill Tutt and Greg Stein cowrote Python2C, which they
  > have been continuing to work on at (http://www.mudlib.org/~rassilon/p2c/).
  > The other player is John Aycock. John declared he would look into run time
  > type instrumentation, which I think should end up forming some sort of a
  > JIT for Python. He lives at: (http://gulf.uvic.ca/~aycock/) 
* 2000 Basil
  * https://sourceforge.net/projects/basil/ - No files, no VCS
  * http://wiki.c2.com/?BasilProject
  * http://wiki.c2.com/?BasilProjectLog
* 2002-2011 [Psyco](http://psyco.sourceforge.net/), https://bitbucket.org/arigo/psyco
  * Was actually used in production for many projects
* 2002-2003 UCPy compiler + Mamba VM
  * [UCPy: Reverse-Engineering Python](https://pages.cpsc.ucalgary.ca/~aycock/papers/ucpy.pdf)
* 2003, active [PyPy](https://bitbucket.org/pypy/pypy)
* 2004-2004 Starkiller
  * [Faster than C: Static Type Inference with Starkiller](http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.95.3786)
* 2008, active [Shedskin](https://github.com/shedskin/shedskin)
* 2009-2010 Unladen Swallow
  * [Postmortem](http://qinsb.blogspot.com/2011/03/unladen-swallow-retrospective.html)
* 2011, active [Nuitka](https://github.com/Nuitka/Nuitka)
* 2015-2015 https://github.com/lukasmartinelli/py14 - Python to C++ 14 transpiler
* 2016-2017 https://github.com/darius/tailbiter - Simple teaching metacircular bytecode compiler
  * [Originally](https://github.com/darius/500lines/tree/master/bytecode-compiler)
    for book "500 Lines or Less" (didn't fit)

SIGs
====
ftp://ftp.ntua.gr/mirror/python/sigs/compiler-sig/dev-day-notes.txt

PEPs
====
* https://www.python.org/dev/peps/pep-0266/
* https://www.python.org/dev/peps/pep-0267/
* https://www.python.org/dev/peps/pep-0280/
* https://www.python.org/dev/peps/pep-0329/

* https://www.python.org/dev/peps/pep-0510/

* https://www.python.org/dev/peps/pep-0511/


Static Analysis
===============

* https://github.com/sdiehl/subpy - Subpy is a library for defining subsets
of the Python language and querying ASTs for language-level properties that
are specified as sets of features.


Parsers
=======

* https://github.com/python/typed_ast - Modified fork of CPython's ast module
  that parses `# type:` comments.
* https://github.com/m-labs/pythonparser - "Parses source code into an AST
  that is a superset of Python’s built-in ast module".
* https://github.com/lark-parser/lark/blob/master/examples/python3.lark - Python3
  grammar for Lark parser.

---
This list is compiled and maintained by Paul Sokolovsky, and released under
[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
