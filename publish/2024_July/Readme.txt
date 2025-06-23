Viewing
****************************
open index.html in any web browser.
You can't open it in sharepoint. Instead use windows explorer to navigate to:
\IRF Research - Documents\1. Current Projects\22-029 HRF Legacy Data - Indicator Dashboard\Output\EconUpdate
(the exact path will depend on your user name, the prefix to that path for me is: C:\Users\rw437\The University of Newcastle\)


Commenting
****************************
A word document is included with the main text and structure. 
You can use this (with track changes on) to make suggestions or comments. 
Please save it with a different file name to ensure that any changes are not overwritten/lost.

Editing
****************************
The markdown file index.qmd is the main file for editing content. It can be opened with any text editor.

With markdown we can generate html or pdf or word documents from the same source, and it is much easier to edit than html directly.


Content
****************************
index.html is the web-facing content, and references files in
./index_files/
index.html is auto-generated and not for editing.

figures which are referenced in index.html are stored in the directory
./html_figs/
Figures are generated using code to produce interactive plotly figures. The figure files are self-contained html files. 

SVG and JPG copies are also producedfor use in the word doc (however, they are not interactive). Copies of these files are found in
./jpegs/


Rendering and copying
****************************
.bat files are provided for rendering to docx and html (producing html and docx output from the markdown files). These will overwrite any files that already exist.
There is code that also copies the files across from the originals to the jpeg folder based on those chosen in the html_figs folder (just run the copy_jpegs.py)


Richard Wood
July 2023
richard.wood@newcastle.edu.au

