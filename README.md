# LATEX_Template
A nice custome LATEX template with clean structure. Some custom commands were added to enable working in group comfortably - striking through unwanted text and writing comments in different color.

Custom commands:
\hh{} - colors the enclosed text in red to alert something to yourself/other teammate.
\im{} - colors the enclosed text in green. Personally I like to write down what images should be inserted and deal with it in the end (cross-references & implementation), a different color is useful for that.
\del{} - strike through the enclosed text. the ulem package is needed for that. NOTE the ulem package changes the behaviour of \emph{} by making it an underline.
\sh{} - colors the enclosed text in blue and adds a new line before and after the text (i.e. to seperate the comment text from the original). The text starts with 3 asterisks. This command is used for writing comments between teammates. For each additional teammate it is recommanded to duplicate this command and change the color with a different name.
\sectionInput{} - shortcut to the 'Section' folder.
\singfig{}{}{}{}{} - a short way to present a display picture. The input parameters are: image_name, placement, height, width, caption. The label is set as fig:image_name.
\singfig{}{}{}{}{}{}{}{} - a short way to present 2 figures next to each other. The input parameters are: placement of duo, minipage width, first image_name, width within minipage for first image, caption of first image, second image_name, width within minipage for second image, caption of second image. The labels are set as the image names fig:first/second image_name
