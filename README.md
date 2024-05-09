# A second course in LaTeX

These are the extended lecture notes for a PhD-level LaTeX course
lectured by [Petri Laarne](https://petri.laarne.fi).
Despite the target audience, these notes are hopefully useful to anybody
who has already some LaTeX experience; in particular MSc students writing their theses.

We do not cover any really advanced topics,
but try to illustrate the best practices of LaTeX in real academic writing.
During that, we do also see some of the internal workings of LaTeX.

The first implementation of this course was at University of Helsinki in May 2024
under the name "Advanced LaTeX Course".
As mentioned above, this is a misnomer, and hence the name of these notes.


## Building these notes

The main file is `notes/2nd-course-in-latex.tex`.
It must be compiled with XeLaTeX or LuaLaTeX.

**Before compiling the main file**, you need to compile all files in the `notes/examples` folder.

The bibliography is compiled with legacy BibTeX for unfortunate technical reasons:
my university computer's security policies are incompatible with the binary packer used by `biber`.
You can use `biber` by removing `backend=bibtex`
from the `\RequirePackage` command for `biblatex` in `notes/latexcourse.sty`.


## Contributing

Typo fixes and suggestions are appreciated.
However, I will not merge any major content additions or restructurings;
these notes are somewhat tied to the course I teach.
You are free to fork these notes as long as you respect the Creative Commons license.


## What about the other course materials?

If you are planning to lecture a course based on these notes,
you can contact me for the curriculum and exercise sheets used in my implementation.

Even less effort: If you would like me to teach the course at your institution,
please contact me and let's see if we can work something out!
