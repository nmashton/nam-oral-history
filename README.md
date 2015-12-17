# NAM Oral History

Converting the entirety of the [*Works and Days* oral history of
the New American Movement](worksanddays.net/W&D 2010.html) to structured
plaintext.

## Contents

Each article is encoded as a [Pandoc Markdown](http://rmarkdown.rstudio.com/authoring_pandoc_markdown.html)
document (to take advantage of Pandoc Markdown's footnotes, citations, and other
useful features not offered by standard Markdown).

Documents are filed according to section and order within section.

## How to use

Build process still under development.

To manually compile a file, use [Pandoc](http://pandoc.org), like so:

    pandoc --filter pandoc-citeproc src/00/00/cohen.md -f markdown -t html -s -o cohen.html

## To do

There are still many, many documents to create.

These documents should be inserted into a static site generator that can
generate HTML from the Markdown. A suitable generator should be found, and
this repo should be restructured to accommodate its architectural pattern.

## Licensing

All contents property of Works and Days. Used with permission of the publisher.
