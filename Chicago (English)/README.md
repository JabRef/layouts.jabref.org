# Chicago Manual of Style and Turabian's Manual Style

The Chicago Manual of Style and Kate Turabian’s A Manual for Writers of Term Papers, Theses, and Dissertations served as the basis for the preparation of the Chicago and Turabian plugins.
Available in both Spanish and English, the plugins add up to four.
Contrary to the claim in the back cover of the Turabian manual, separate plugins are necessary because the styles, despite their strong similarities, are not reflections of each other.
Each laoyut prepares output in the Rich Text Format (RTF) for the two basic systems.

	author-date			(two filters)
	notes and bibliography 		(three filters)

The plugins prepare entries that the user can export to the clipboard and then paste into a document for word processing in Word, Word Perfect, Open Office, etc. These plugins prepare exports for the following entry types of JabRef:  

- article
- inproceedings
- phdthesis
- book
- incollection
- unpublished
- conference
- mastersthesis
- electronic

## Author-date style

According to both manuals, the author-date system consists of two distinct parts. Accordingly, each plugin contains filters for 

- reference lists for the complete list of sources
- text citations enclosed in parenthesis.

The reference list export feature consists of the following twelve files:

- Chicago.reference.article.layout
- Chicago.reference.begin.layout
- Chicago.reference.book.layout
- Chicago.reference.conference.layout
- Chicago.reference.electronic.layout
- Chicago.reference.end.layout
- Chicago.reference.incollection.layout
- Chicago.reference.inproceedings.layout
- Chicago.reference.layout
- Chicago.reference.mastersthesis.layout
- Chicago.reference.phdthesis.layout
- Chicago.reference.unpublished.layout

The text citation export feature consists of the following twelve files that serve as pointers to the reference list:

- Chicago.text.article.layout
- Chicago.text.begin.layout
- Chicago.text.book.layout
- Chicago.text.conference.layout
- Chicago.text.electronic.layout
- Chicago.text.end.layout
- Chicago.text.incollection.layout
- Chicago.text.inproceedings.layout
- Chicago.text.layout
- Chicago.text.mastersthesis.layout
- Chicago.text.phdthesis.layout
- Chicago.text.unpublished.layout


## Note and bibliography style

Both manuals consider three distinct formats for an entry:

- biblio for bibliographies
- footend for footnotes and endnotes
- footend short for subsequent notes or works with full bibliographies.

The bibliography export feature consists of the following twelve files:


- Chicago.biblio.article.layout
- Chicago.biblio.begin.layout
- Chicago.biblio.book.layout
- Chicago.biblio.conference.layout
- Chicago.biblio.electronic.layout
- Chicago.biblio.end.layout
- Chicago.biblio.incollection.layout
- Chicago.biblio.inproceedings.layout
- Chicago.biblio.layout
- Chicago.biblio.mastersthesis.layout
- Chicago.biblio.phdthesis.layout
- Chicago.biblio.unpublished.layout


The full citation for the export of footnotes and endnotes-feature consists of the following twelve files. This feature prepares the complete reference that accompanies the first citation of a bibliographic entry in a work lacking a full bibliography.

- Chicago.footend.article.layout
- Chicago.footend.begin.layout
- Chicago.footend.book.layout
- Chicago.footend.conference.layout
- Chicago.footend.electronic.layout
- Chicago.footend.end.layout
- Chicago.footend.incollection.layout
- Chicago.footend.inproceedings.layout
- Chicago.footend.layout
- Chicago.footend.mastersthesis.layout
- Chicago.footend.phdthesis.layout
- Chicago.footend.unpublished.layout


The shortened citation for the export of footnotes and endnotes-feature consists of the following twelve files.

- Chicago.footend.short.article.layout
- Chicago.footend.short.begin.layout
- Chicago.footend.short.book.layout
- Chicago.footend.short.conference.layout
- Chicago.footend.short.electronic.layout
- Chicago.footend.short.end.layout
- Chicago.footend.short.incollection.layout
- Chicago.footend.short.inproceedings.layout
- Chicago.footend.short.layout
- Chicago.footend.short.mastersthesis.layout
- Chicago.footend.short.phdthesis.layout
- Chicago.footend.short.unpublished.layout


## Abstract and note filters

The user may wish to use the "abstract" field to summarize and annotate a particular entry.
The following feature presents the entry in the bibliography format followed by the "abstract" field.
The feature follows the note and bibliography style.

- Chicago.abstract.article.layout
- Chicago.abstract.begin.layout
- Chicago.abstract.book.layout
- Chicago.abstract.conference.layout
- Chicago.abstract.electronic.layout
- Chicago.abstract.end.layout
- Chicago.abstract.incollection.layout
- Chicago.abstract.inproceedings.layout
- Chicago.abstract.layout
- Chicago.abstract.mastersthesis.layout
- Chicago.abstract.phdthesis.layout
- Chicago.abstract.unpublished.layout


Finally, some user may wish to use the "note" field for other purposes as to write down the call number, ISBN or other properties of an entry.
The following feature presents the reference in the bibliography format followed by the "note" field.

- Chicago.note.article.layout
- Chicago.note.begin.layout
- Chicago.note.book.layout
- Chicago.note.conference.layout
- Chicago.note.electronic.layout
- Chicago.note.end.layout
- Chicago.note.incollection.layout
- Chicago.note.inproceedings.layout
- Chicago.note.layout
- Chicago.note.mastersthesis.layout
- Chicago.note.phdthesis.layout
- Chicago.note.unpublished.layout


## Installation

The seven features are available in both the English and Spanish versions of the Turabian and Chicago laoyut files.
Please note that the `README.md` file remains in English but phrases as "Paper presented at" appear in Spanish in the layout files.

Please see the top README.md for installation instructions.
In short, use Options -> Manage Custom Imports...


## Notes on the filters

- The user should consider the output from the plugins as a draft that may require some fine adjustment from the word processor.
- Reference lists and bibliographies require a hanging indent that the layout options do not seem to offer. Once the entries are in the word processor, use the hanging indent function.
- In the note and bibliography format, if the author's or editor's first or middle name is an initial or ends with one, two periods will end the field. One corresponds to the initial and the other for the end of field.
- The Turabian manual requires the access date for all web online sources.  Enter the access date in the “comment” field of all electronic entry types. The Chicago plugins do not export the contents of the “comment” field.
- To print correctly the names of authors that lack surnames -- such as NGOs and corporations -- add a comma at the end of the name in the author or editor field.
- In the author-date format, delete the colon to make newspapers and magazines fit the article layout.

JabRef automatically wraps the text by omitting line breaks. To overcome this default, when exporting fields such as abstract or note, the user must insert:

    \\
    \\
	
in the text to make a line break and a double space.

    \newline
    \newline

Will also do it.

## Acknowledgments

Morten Omholt Alver generously prepared the initial source code and the Java plugin to host the filters.
In the preparation of these plugins, I have followed JabRef's, “Custom export filters,” SourceForge.net, 29 Jan. 2012, <http://jabref.sourceforge.net/help/CustomExports.php>. 
I have also relied on gottfried's Harvard filter (vosgerau@uni-tuebingen.de) and Matthias Stürmer MIS Quarterly-filter which are both native to JabRef.
The [Department of Sociology and Anthropology of the University of Puerto Rico](http://urrp.academia.edu/Departments/Sociology_and_Anthropology) funded this work. 
