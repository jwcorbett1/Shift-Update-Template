# Shift-Update-Template
Formatter for once-per-shift email report to NCDOT management.

This tool is now primarily written in Javascript with some CSS mixed in to handle formatting.  It is still packaged into an HTML file so TMC operators can easily open it at any workstation without "installing custom software".  The file is organized from bottom to top-level - a human reading through this file should generally see a constant or definition before it is used at a higher level.

I have used Javascript objects extensively here mostly because I had not used them much before this project.  It also seemed to fit the logical structure of the data and execution flow fairly well, and it facilitated generating HTML as needed when additional entry lines are added by the user.  See the "toHtml()" method in the InputField class and its subclasses for additional details about how this is accomplished.
