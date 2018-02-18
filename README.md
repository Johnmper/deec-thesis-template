# Thesis Template


## Template Structure:

```
LaThesis
====================
\- thesis.tex
\- C00-Informative
|	\- cover.tex
|	\- title1.tex
|	\- title2.tex
|	\- summary.tex			
|	\- abstract.tex
|	\- listofacronyms.tex
|	\- bibliography.bib
|	\- appendix.tex
|
\- C01-Introduction				
|	\- introduction.tex
|	\- Images
|		\- img*.png
|
\- C02-Background
|	\- background.tex
|	\- Images
|		\- img*.png
|
\- C03-Methods
|	\- methods.tex
|	\- Images
|		\- img*.png
|
\- C04-Results
|	\- results.tex
|	\- Images
|		\- img*.png
|
\- C05-Discussion
|	\- discussion.tex
|	\- Images
|		\- img*.png
|
\- C06-Conclusions
|	\- conclusions.tex
|	\- Images
|		\- img*.png
|
\- C07-Recommendations
|	\- recommendations.tex
|	\- Images
|		\- img*.png

```

## Notes:


* Each chapter has its own **Figures** folder, reducing some image naming complexity.
* Use *includeonly* to compile a single chapter without losing labels from the other chapters.
