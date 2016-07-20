This is a fork of the original. This program does not require page argument to be compulsory and will parse all the pages in such case.

To install :  sudo python setup.py install

usage: pdf-table-extract [-h] -i INFILE -o OUTFILE
                         [--greyscale_threshold GREYSCALE_THRESHOLD] [-p PAGE]
                         [-c CROP] [--line_length LINE_LENGTH]
                         [--bitmap_resolution BITMAP_RESOLUTION] [-name NAME]
                         [-pad PAD] [-white WHITE] [-black BLACK] [-bitmap]
                         [-checkcrop] [-checklines] [-checkdivs] [-checkcells]
                         [-colmult COLMULT] [-boxes]
                         [-t {cells_csv,cells_json,cells_xml,table_csv,table_html,table_chtml,table_list}]
                         [--whitespace {none,normalize,raw}] [--traceback]

*PDF Table Extraction Utility.* Analyses a page in a PDF looking
for well delineated table cells, and extracts the text in each cell.
Outputs include JSON, XML, and CSV lists of cell locations, shapes,
and contents, and CSV and HTML versions of the tables. This utility
is intended to be the first step in automatically processing data
in tables from a PDF file, and was originally designed to read the
tables in ST Micro’s datasheets. The script requires pyPdf, numpy and poppler
(pdftoppm and pdftotext)

###License
[MIT Expat](http://ashimagroup.net/os/license/mit-expat)

###Tags
[Utilities](http://ashimagroup.net/os/tag/utilities)


