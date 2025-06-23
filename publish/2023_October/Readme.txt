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
./figs/
Figures are generated using code to produce interactive plotly figures. The figure files are self-contained html files. SVG copies are also produced, and used in the word doc (however, they are not interactive).



Richard Wood
July 2023
richard.wood@newcastle.edu.au



** TO DO ** July 19th
- add building approval figures
- embed all essential meta into the figure htmls.
- try to compile code into functions if possible, and improving naming and saving of datasets