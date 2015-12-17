# NAM Oral History

Converting the entirety of the [*Works and Days* oral history of
the New American Movement](worksanddays.net/W&D 2010.html) to structured
plaintext.

## Contents

Each article is encoded as a [Pandoc Markdown](http://rmarkdown.rstudio.com/authoring_pandoc_markdown.html)
document (to take advantage of Pandoc Markdown's footnotes, citations, and other
useful features not offered by standard Markdown).

Documents are filed according to section and order within section.

## Install

Dependencies are handled via `npm`. To install, simply run `npm install`.

## Build

The project uses [Metalsmith](http://www.metalsmith.io/) to build HTML.

To build, run `npm run build`.

## To do

There are still many, many documents to create.

Beyond that, the build process should be improved as appropriate (e.g.)
fleshed out to generate a proper, functioning site instead of just some raw HTML.

Also, I'm *pretty sure* this is the wrong way to use `metalsmith-pandic` (or its
underlying `pdc` system). That should be improved upon.

## Licensing

All contents property of Works and Days. Used with permission of the publisher.
