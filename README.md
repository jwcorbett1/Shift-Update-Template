# Shift-Update-Template
Formatter for once-per-shift email report to NCDOT management.

This tool is now primarily written in Javascript with some CSS mixed in to handle formatting.  It is still packaged into an HTML file so TMC operators can easily open it at any workstation without installing custom software.  The file is organized bottom-up - a human reading through this file from beginning to end should generally see constants and definitions before they are used at logically higher levels.

I used Javascript classes extensively throughout this tool.  Doing so fit the structure of the data and execution flow, and it facilitated generating new HTML as needed when additional entry lines are added by the user.  See the "toHtml()" method in the InputField class and its subclasses for additional details about how this was accomplished.
