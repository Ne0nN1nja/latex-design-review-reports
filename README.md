# latex-design-review-reports
LaTeX template for HA design review reports, and the reports themselves

[//]: # (TODO: include instructions on how to set up the environment, how to contribute to a report, and how to make a new report)

Quick VSCode LaTeX installation tutorial:

Install TexLive. This step may take a while.

Install the Font Files Saira and Libre Franklin. These can be found in the PSP branding kit. Remember to install file for all users by right clicking the font file and clicking on "Install for All Users". This is important.

Install VSCode

Using VSCode:
Install LaTeX Workshop extension.

Click on the settings of LaTeX Workshop (gear symbol)

Extension Settings

Find Bibtex > settings.json
Search bar should work for this part.

Open file.

Paste [insert settings code, get from Evan Rittner or Steven Huang] into the file. Keep the first and last brace in the file.

Save

Go back to report.tex tab

Click TeX extension on sidebar with report.tex open.

Click the dropdown menu for Build LaTeX project.

Click on the "play" button next to xelatex.

If no errors arise, the report.pdf should be updated with any changes made to the tex file. Saving the file should also recompile the project again.
