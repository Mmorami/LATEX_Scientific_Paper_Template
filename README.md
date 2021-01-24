# LaTeX Template
LaTeX is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation. LaTeX is the de facto standard for the communication and publication of scientific documents. This LaTeX template aim enhance the experience of groups collaborating on the same document(s). It include commands such as, striking-though text and adding comments in different color.

[add gif here]

## Installation

LaTeX is not a stand-alone typesetting program in itself, but a document preparation software that runs on top of TEX.
LaTeX is distributed through CTAN servers or comes as part of many easily installable and usable TeX distributions provided by TeX User Group (TUG) - like [TEX Live](https://www.tug.org/texlive/), and [Mik TEX](https://miktex.org/).
For more distributions visit http://www.tug.org/interest.html#free .

It is also possible to use online service like [Overleaf](https://www.overleaf.com/) and [Papeeria](https://www.papeeria.com/). 

For more information and directions please visit https://www.latex-project.org/get/ .

## Usage

```
import ulem # NOTE the ulem package changes the behaviour of \emph{} to underline.

\hh{} # colors text in red. Use to alert something to yourself/teammate.
\im{} # colors text in green. Use to memo something to yourself/teammate.
\sh{} # colors text in blue, and adds a new line before and after the text. Use to comment on something. You can update this command to include multiple colors for different teammates.
\del{} # strike-through text.
\sectionInput{} # shortcut to the 'Section' folder.
\singfig{}{}{}{}{} # a short way to present a display picture. The input parameters are: image_name, placement, height, width, caption. The label is set as fig:image_name.
\doublefig{}{}{}{}{}{}{}{} # a short way to present 2 figures next to each other. The input parameters are: placement of duo, minipage width, first image_name, width within minipage for first image, caption of first image, second image_name, width within minipage for second image, caption of second image. The labels are set as the image names fig:first/second image_name
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
