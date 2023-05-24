# tikz-network
A tool to visualize complex networks in LaTeX.

| Package:           | tikz-network                                                           |
| ------------------ | -----------                                                            |
| **Date:**          | 15 August 2019                                                          |
| **Authors:**       | Jürgen Hackl                                                           |
| **Contact:**       | hackl.j@gmx.at                                                         |
| **Web site:**      | https://github.com/hackl/tikz-network/                                 |
| **Documentation:** | [manual](https://github.com/hackl/tikz-network/blob/master/manual.pdf) |
| **Copyright:**     | This document has been placed in the public domain.                    |
| **License:**       | GNU General Public Licence.                                            |
| **Version:**       | 1.1                                                                    |

## Purpose

In recent years, complex network theory becomes more and more popular within the scientific community. Besides a solid mathematical base on which these theories are built on, a visual representation of the networks allow communicating complex relationships to a broad audience.

Nowadays, a variety of great visualization tools are available, which helps to structure, filter, manipulate and of course to visualize the networks. However, they come with some limitations, including the need for specific software tools, difficulties to embed the outputs properly in a `LaTeX` file (e.g. font type, font size, additional equations and math symbols needed,...) and challenges in the post-processing of the graphs, without rerunning the software tools again.

In order to overcome this issues, the package `tikz-network` was created. Some of the features are:

- `LaTeX` is a standard for scientific publications and widely used
- beside `LaTeX` no other software is needed
- no programming skills are needed
- simple to use but allows 100% control over the output
- easy for post-processing (e.g. adding drawings, texts, equations,\dots)
- same fonts, font sizes, mathematical symbols, \dots as in the document
- no quality loss of the output due to the pdf format
- networks are easy to adapt or modify for lectures or small examples
- able to visualize larger networks
- three-dimensional visualization of (multilayer) networks
- compatible with other visualization tools

## ToDo

### Code to fix
- [ ] change default entries for Boolean options in the vertices file.

### Documentation
- [ ] add indices to the manual.
- [ ] add an extended tutorial/example to the document.
- [ ] clean-up and document the .sty file.


### Features
- [ ] add a spherical coordinate system

### Add-ons
- [ ] add QGIS to tikz-network compiler


## Changelog
| Version | Changes                                                                                         |
|---------|-------------------------------------------------------------------------------------------------|
| 0.1     | initial commit                                                                                  |
| 0.2     | changed the package name to tikz-network                                                        |
| 0.3     | added commands `\Text` and `\Plain`, plus smaller changes in the commands `\Vertex` and `\Edge` |
| 0.4     | renamed `\Plain` to `\Plane` and added commands to change the label font, size and color        |
| 0.5     | added a description of the Python module [network2tikz](https://github.com/hackl/network2tikz)  |
| 1.0     | upload to the CTAN server                                                                       |
| 1.1     | fixed csv input and added manual examples as standalone figures to git                          |
