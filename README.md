# Paper-Template
## Conference on Neural Information Processing Systems

From [Wikipedia](https://en.wikipedia.org/wiki/Conference_on_Neural_Information_Processing_Systems)

The Conference and Workshop on Neural Information Processing Systems (NIPS) is a machine learning and computational neuroscience conference held every December. The conference is currently a double-track meeting (single-track until 2015) that includes invited talks as well as oral and poster presentations of refereed papers, followed by parallel-track workshops that up to 2013 were held at ski resorts.
## NIPS 2017 Latex Template
Check [here](https://nips.cc/Conferences/2017/PaperInformation/StyleFiles) for details.

NOTE: The LaTeX style for NIPS 2017 has changes from previous years. Please use the correct version!

Please read the general instructions for authors before writing your paper.

You should use the following files for your submission:

nips_2017.tex -- LaTeX template.
nips_2017.sty -- style file for LaTeX 2e Microsoft Word, RTF, and LaTeX 2.09 are no longer supported.
nips_2017.pdf -- PDF output generated by running “pdflatex”.
All NIPS submissions must be made via the electronic submissions system. Make sure that your paper prints well and consult section 6 in the example .tex file for information regarding fonts. All submissions must be in PDF format. The maximum file size for submissions is 100MB. Papers are limited to eight pages, including figures and tables, in the NIPS style. Additional pages containing only cited references are allowed. Submissions that do not follow these guidelines (in particular by exceeding the page limit or increasing the page size) will be rejected without review.

You are strongly encouraged to test the formatting of your paper using the NIPS paper checker (well in advance of the deadline due to server limitations).

Reviewing will be double-blind
The reviewers will not know the identities of the authors. It is the responsibility of the authors to ensure the proper anonymization of their paper. Please note that display math in bare TeX commands will not create correct line numbers at submission time. Please use LaTeX commands for unnumbered display math (or, equivalently with AMSTeX). [Here](https://tex.stackexchange.com/questions/503/why-is-preferable-to) and [Here](https://nips.cc/http://tex.stackexchange.com/questions/40492/what-are-the-differences-between-align-equation-and-displaymath)

Camera-ready papers
Please use the nips_2017.tex latex template (which uses nips_2017.sty) and compile with the [final] option:

\usepackage[final]{nips_2017} % produce camera-ready copy

Note that the \nipsfinalcopy command is now obsolete.

program-chairs@nips.cc

#Note: to remove line numbers remove line 58, 50 and 60 (   % line numbers for submission
  \RequirePackage{lineno}
  \linenumbers ) from nips_2017.sty or use nips_2017_new.sty 
