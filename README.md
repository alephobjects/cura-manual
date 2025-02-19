cura-manual
===========

This is the LaTeX source code for the Cura LulzBot Edition User Manual


Known used packages required to compile the PDF manual on a Debian based system:

doxygen-latex
feynmf
lacheck
latex-beamer
latex-xcolor
preview-latex-style
prosper
texlive-latex3
texlive-latex-base
texlive-latex-base-doc
texlive-latex-extra
texlive-latex-extra-doc
texlive-latex-recommended
texlive-latex-recommended-doc
tipa
xindy 

Create a text document with the required packages:

$: vi packages

doxygen-latex feynmf lacheck latex-beamer latex-xcolor preview-latex-style prosper texlive-base texlive-binaries texlive-common texlive-doc-base texlive-doc-en texlive-extra-utils texlive-fonts-extra texlive-fonts-extra-doc texlive-fonts-recommended texlive-fonts-recommended-doc texlive-font-utils texlive-generic-recommended texlive-humanities texlive-humanities-doc texlive-latex3 texlive-latex-base texlive-latex-base-doc texlive-latex-extra texlive-latex-extra-doc texlive-latex-recommended texlive-latex-recommended-doc texlive-luatex texlive-metapost texlive-metapost-doc texlive-pictures texlive-pictures-doc texlive-pstricks texlive-pstricks-doc texlive-xetex tipa xindy texlive-humanities texlive-latex-extra

If you're not familiar with vi/vim, use your desired text editor.


Install the packages:

$: sudo apt-get install $(cat packages)

If you encounter errors, or missing dependencies, install them one by one, or contact Support@Lulzbot.com for further assitance.



Translations:

If you'd like to translate the manual, please feel free to do so! Fork the project to a new branch. 


Generating the manual:

At the root directory of the manual, (../cura-manual/) in a terminal run:
$: ./make-Manual-multiple.sh

If you encounter any errors, look for the file name/line entry.


Copyright 2015, Aleph Objects, Inc.

License: CC-BY-SA 3.0
