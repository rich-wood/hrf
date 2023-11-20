# hrf

Generate html files, using quarto in the folder ./generate/
All edits happen in the ./generate/ folder
Edit the .qmd files, not the html.

html files write to ./publish/ directory.
copy images as needed (generate these externally)


Info for rendering (creating html)
Render (see next point) to both html and docx.
	- rendering requires the quarto program installed (see below).
	- you can render the whole project direct from the command line after quarto is installed.
		- cd to working directory
		- type "quarto render"
	- alternatively you can render individual .qmd using Rstudio if you have it installed. Just open the .qmd file in Rstudio and click the "render" button.


Quarto is available at:
https://quarto.org/docs/get-started/
Rstudio is available at:
https://posit.co/download/rstudio-desktop/
You might also need to install some packages in Rstudio.

