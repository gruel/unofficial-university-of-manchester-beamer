Unofficial University of Manchester Beamer Theme
------------------------------------------------
Provides a (very nice looking) Beamer theme that matches the official
University of Manchester PowerPoint Style.

"University of Manchester" and associated logos are copyright of the
University of Manchester -- please see http://www.brand.manchester.ac.uk

To use the theme, ensure the following files are copied into somewhere like:
~/texmf/tex/latex/beamer/themes or /usr/share/texmf/...

- beamercolorthemeUniversityOfManchester.sty
- beamerfontthemeUniversityOfManchester.sty
- beamerinnerthemeUniversityOfManchester.sty
- beamerouterthemeUniversityOfManchester.sty
- beamerthemeUniversityOfManchester.sty
- TAB_allwhite.pdf
- TAB_col_white_background.pdf

Then run `$ texhash'.

You can then use the theme as:
\documentclass[t]{beamer}
\usetheme[..options..]{UniversityOfManchester}

Where the options are:
- dark
- darktitle
- cabin [Replaces the default font with Cabin, much nicer!]

The following colours are defined for your use:
- uompurple
- uomyellow
- uomgrey

Based partially upon http://nschloe.blogspot.de/2009/04/ua-beamer-theme_15.html,
This file may be distributed and/or modified
1. under the LaTeX Project Public License and/or
2. under the GNU Public License.