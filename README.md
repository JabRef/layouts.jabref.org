# .layout files for JabRef

This repository contains laoyut files used for JabRef.
The can be used to create custom export filters as described at <https://docs.jabref.org/collaborative-work/export/customexports>.
One can use the [Export-Filter Editor for Jabref](https://sourceforge.net/projects/efe/) to quickly create ones own export filter.

## Table of Contents

<!-- generated by https://github.com/jonschlinkert/markdown-toc using markdown-toc -i README.md -->

<!-- toc -->

- [Howto](#howto)
- [Other Layout Files](#other-layout-files)
  * [APA export filter](#apa-export-filter)
  * [CSV export filter with Mendeley tags](#csv-export-filter-with-mendeley-tags)
  * [Daniel Haertle's HTML export filter](#daniel-haertles-html-export-filter)
  * [Mark Schenk's HTML export filters](#mark-schenks-html-export-filters)
  * [Truong X. Nghiem's HTML export filter](#truong-x-nghiems-html-export-filter)
- [Available Layout Files](#available-layout-files)
  * [Chicago Manual of Style](#chicago-manual-of-style)
  * [Dev_Biology](#dev_biology)
  * [Edward Elgar](#edward-elgar)
  * [Gene](#gene)
  * [International Journal of Greenhouse Gas (IJoGGC) export filters](#international-journal-of-greenhouse-gas-ijoggc-export-filters)
  * [J_Biol_Chem](#j_biol_chem)
  * [Journal of experimental Botany](#journal-of-experimental-botany)
  * [Kate Turabian’s A Manual for Writers of Term Papers, Theses, and Dissertations](#kate-turabians-a-manual-for-writers-of-term-papers-theses-and-dissertations)
  * [Mechan_Development](#mechan_development)
  * [Mol_Genet_Gen](#mol_genet_gen)
  * [Nature](#nature)
  * [The Plant Cell](#the-plant-cell)
  * [Plant_Physiology](#plant_physiology)
  * [PLos_Biology](#plos_biology)
  * [Proceedings of the National Academic Sciences](#proceedings-of-the-national-academic-sciences)
  * [The_Plant_Journal](#the_plant_journal)
- [License](#license)

<!-- tocstop -->

## Howto

- Download <https://github.com/JabRef/layouts.jabref.org/archive/master.zip>.
- Extract `master.zip`
- JabRef > Options > Manage custom exports > Add new
  - Export name: its up to you (e.g., `IJoGGC`)
  - Main layout file: Choose the right `.layout` file. (e.g., `IJoGGC.layout`)
    - Browse to your folder, where you safed the layout files
	- File extension: `.rtf`
  - `OK`
- If you now you go to File > Export, Jabref will open a window where you can choose different types of exportfilters below. Select Files of type: IJoGGC(*.rtf).

For some articles you need additional name-formatters (Options-->Preferences-->name formatter).
That is noted at addtional name formatter.


## Other Layout Files


### APA export filter

Russell Almond's APA export filter provides an export filter that is close to the American Pychological Association (APA) guidelines. It exports the references in Rich Text Format (rtf).

[Download Russell Almond's APA export filter](http://ralmond.net/APAish/)

### CSV export filter with Mendeley tags
Cynthia D'Angelo's CSV export filter with Mendeley tags provides an export filter that allows for exporting Mendely tags. It exports the refencence in csv format (i.e. spreadsheet- compatible).

[Dowload Cynthia D'Angelo's CSV export filter with Mendeley tags](https://cynthiadangelo.com/2012/10/22/exporting-mendeley-tags/)


### Daniel Haertle's HTML export filter

Daniel Haertle's HTML export filter provides an HTML listing of your reference list. The output looks [like this](http://haertle.ch/publications/).

[Download Daniel Haertle's HTML export filter](http://haertle.ch/programs/jabref/)


### Mark Schenk's HTML export filters

Mark Schenk's HTML export filters provide HTML listings of your reference list. The exported HTML comes complete with scripts for quick filtering of the list.

_Note: some of Mark Schenk's filters are distributed with JabRef as standard export filters._

[Download Mark Schenk's HTML export filters](http://www.markschenk.com/tools/jabref/)


### Truong X. Nghiem's HTML export filter
Truong X. Nghiem's HTML export filter provides an HTML listing of your reference list that does not contain a header nor a body. Its purpose is to be included in other HTML files or in text-to-html source files (e.g. Jemdoc). The output looks [like this](http://txn.name/publications.html).

[Download Truong X. Nghiem's HTML export filter](http://txn.name/publist.html)


## Available Layout Files

At some layout files, some layouts might be missing.
For instance, the book layout is missing at PNAS.


### Chicago Manual of Style

Documentation is at [Chicago (English)/README.md](Chicago%20(English)/README.md).

- Directory: [Chicago (English)](Chicago%20(English)/) and [Chicago (Spanish)](Chicago%20(Spanish)/)
- Author: Juan José Baldrich


### Dev_Biology

- File extension: `.rtf`
- Author: Marten Kooiker


### Edward Elgar

- Directory: [Edward Elgar](Edward%20Elgar/)
- Author:  Christian Bartolomaeus


### Gene

- File extension: `.rtf`
- Author: Marten Kooiker


### International Journal of Greenhouse Gas (IJoGGC) export filters

This filter is a modified version of Edwared Elgar's export filters.
It formats the exported .rtf file into the format required by lots of Elsevier Journals.

- File extension: `.rtf`
- Main layout file: [IJoGGC.layout](International%20Journal%20of%20Greenhouse%20Gas%20(IJoGGC)/IJoGGC.layout)


### J_Biol_Chem

- File extension: `.rtf`
- Author: Marten Kooiker


### Journal of experimental Botany 

- Directory: [J_of_Exp_Botany/](J_of_Exp_Botany/)
- File extension: `.rtf`
- Addtional name formatter: **J_Exp_Bot**: `*@1..-2@{vv }{ll} {f}, @-1@{vv }{ll} {f}.`
- Author: Marten Kooiker


### Kate Turabian’s A Manual for Writers of Term Papers, Theses, and Dissertations

Documentation is at [Chicago (English)/README.md](Chicago%20(English)/README.md).

- Directory: [Turabian (English)](Turabian%20(English)/) and [Turabian (Spanish)](Turabian%20(Spanish)/)
- Author: Juan José Baldrich

### Mechan_Development

- File extension: `.rtf`
- Author: Marten Kooiker


### Mol_Genet_Gen

- File extension: `.rtf`
- Author: Marten Kooiker


### Nature

- File extension: `.rtf`
- Addtional name formatter: **Nature**: `1@*@{vv }{ll,} {f.}@@2@1@{vv }{ll,} {f.}, @2@{vv }{ll,} {f.},@@3@1@{vv }{ll,} {f.}, @2@{vv }{ll,} {f.},@3@{vv }{ll,} {f.},@@4@1@{vv }{ll,} {f.}, @2@{vv }{ll,} {f.},@3@{vv }{ll,} {f.},@4@{vv }{ll,} {f.},@@5@1@{vv }{ll,} {f.}, @2@{vv }{ll,} {f.},@3@{vv }{ll,} {f.},@4@{vv }{ll,} {f.},@5@{vv }{ll,} {f.},@@*@1@{vv }{ll,} {f.} et al. @2..-1@{}`
- Author: Marten Kooiker


### The Plant Cell

- Directory: [Plant_Cell/](Plant_Cell/)
- File extension: `.rtf`
- Addtional name formatter: **Plant_Cell**: `*@1..-2@{vv }{ll,} {f.}, @-1@and {vv }{ll,} {f.}`
- Author: Marten Kooiker


### Plant_Physiology

- File extension: `.rtf`
- Addtional name formatter: **Plant_phys**: `*@1..-2@{vv }{ll }{f}, @-1@{vv }{ll }{f}`
- Author: Marten Kooiker


### PLos_Biology

- File extension: `.rtf`
- Author: Marten Kooiker


### Proceedings of the National Academic Sciences 

- Directory: [PNAS/](PNAS/)
- File extension: `.rtf`
- Addtional name formatter: **PNAS**: `1@*@{vv }{ll} {f}@@2@1@{vv }{ll} {f}, @2@{vv }{ll} {f}@@3@1@{vv }{ll} {f}, @2@{vv }{ll} {f}, @3@{vv }{ll} {f}@@4@1@{vv }{ll} {f}, @2@{vv }{ll} {f}, @3@{vv }{ll} {f}, @4@{vv }{ll} {f}@@5@1@{vv }{ll} {f}, @2@{vv }{ll} {f}, @3@{vv }{ll} {f}, @4@{vv }{ll} {f}, @5@{vv }{ll} {f}@@*@1@{vv }{ll} {f}, et al. @2..-1@{}`
- Author: Marten Kooiker


### The_Plant_Journal

- File extension: `.rtf`
- Author: Marten Kooiker


## License

The files are subject to the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) if not otherwise noted.

Some files are subject under the terms of the GPL version 2 (or later).
