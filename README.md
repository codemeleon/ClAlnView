# About

AlnViewer is a simple interactive command-line key binding based viewer to display pre-processed multiple sequence alignments. Alnviewer can be used locally or over remote login to visualize one or multiple alignments without leaving the command-line user interface.

A desire to be able to able to visualise large multiple sequence alignments, stored on a remote host, initiated the design of the program.

The program is being developed by the MiDEP group at the [Malawi Liverpool Wellcome Trust Clinical Research Programme](http://www.mlw.medcol.mw/index.php/microbial-ecology.html), as part of the activities of the [H3ABionet Consortium](http://www.h3abionet.org/).


# Dependecies

- Python 3.+ (Not tested on Python 2.+)
- Biopython
- Click
- Pandas

# Installation

python setup install

# Usage

alnviewer --alnpath [aln_file|aln_folder] --alntype [amn|nuc] --undocount num --modified path_for_altered_files


# Key binding

Please press "?" inside the program

![Normal View][i6]

# Screenshots

**Normal view**

![Normal View][i1]

**Reference view**

![Reference View][i2]

**Reference view**

![Mismatch View][i3]

**Genomic location search**

![Genomic Location Search][i4]

**Pattern search**

![Pattern search][i5]

# Licence

GPLv3

# TODOs

- [ ] Mostly speed improvements
- [ ] add option to mark file to copy in different folder

[i1]: figures/NormalView.png "Normal View"
[i2]: figures/Reference_based.png "Reference View"
[i3]: figures/Mismaches.png "Mismatch View"
[i4]: figures/Genomic_Location.png "Genomic Location Search"
[i5]: figures/Pattern.png "Pattern Search"
[i6]: figures/Options.png "Options Page"
