Documentation - MetaboHUB
=======

Metadata
-----------

 * **@name**: Documentation - MetaboHUB
 * **@version**: 0.1
 * **@authors**: Franck Giacomoni, Nils Paulhe
 * **@date creation**: 2014/02/21
 * **@main usage**: create PeakForest documentation (SRS / WebApp / WebServices)

Configuration
-----------

### Requirement:
 * pdflatex (`yum install tetex`), version 3.1415926-2.5-1.40.14 or later

### Get project data:
 * get project data `git clone ssh://git@pfemw3.clermont.inra.fr:dev-team/peakforest-doc-scope_statement.git`

### Generate PDF files:
 * complile all documents: `make all`
 * clean / delete all generated files: `make clean`
 * build "WebService REST guide" file: `make rest`
 * build "Peak Forest Install Guide" file: `make webapp`
 * build "Software Requirement Specification" file: `make srs`

Services provided
-----------

none


Technical description
-----------

none

Notes
-----------

the `make` command create a file (`vc.tex`) used to includ the SHA1 commit ID in the generated PDF file.

********************************************************************************

