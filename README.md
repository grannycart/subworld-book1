
# Manuscript Draft --- A Novel With Some Submarines In It (pre-release version)
* By Mark Torrey


## How to read it:
* Available to read on github pages here:
	* [Subworld Pages](http://grannycart.net/subworld-pages/)
* Or, compile from this source code using pandoc.
	* (Or just read the straight markdown, available in source.)

## Repo contents:
* **cover/**: The cover graphic files.
* **documentation/**: Todo lists and other documentation.
* **full-draft-manuscript/**: Current version of book in markdown. broken out into separate files for each chapter.
* **pseudocode-files/**: Early non-prose drafts.
* **sub-diagrams/**: Digrams of protaganist submarines in book.


## Compilation notes:
* Compiled using pandoc-ebook-template. For instructions see:
	* https://github.com/evangoer/pandoc-ebook-template
	* Also see Makefile for details.
* Basically: 
	1. on a linux box 
	2. make sure you have pandoc and latex installed 
	3. then just run make. This will create an epub, html, pdf, latex, and plain txt version of the book.
	4. These files can be cleaned up a bit by hand. See notes below.
* epub:
	* formatting notes to come
* html:
	* more or less works as compiled by pandoc, but it's not pretty
* pdf:
	* more or less works as compiled by pandoc
* txt:
	* more or less works as compiled by pandoc
* latex:
	* I experimented with creating latex with pandoc and then editing the latex by hand. It was not entirely useful, so I removed this target from the Makefile. See [notes here](experiments-with-latex-formatting.md).
* Diagrams:
	* Eventually these will have to go into Makefile for epub compilation. At the moment that isn't working so great.
	* There is a quick layout in an Inkscape .svg file in the sub-diagrams/ directory. Just open that in Inkscape, save it as a pdf, and then do what you like with it.

## Credits:
* Compiled using pandoc-ebook-template:
	* https://github.com/evangoer/pandoc-ebook-template
* Test readers:
	* Your name here!
	* Or your name here!
	* Or your name here!

[//]: # (* Cover from covervault: * https://covervault.com/)

## Documentation:
* [Notes and todos](documentation/notes_and_todos-subworld_story1)


## License:
* This pre-release version of this book is under a CC license:
* Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
	* CC BY-NC-SA 4.0
	* See: [LICENSE](./LICENSE)
* Future versions may be under some other license.


