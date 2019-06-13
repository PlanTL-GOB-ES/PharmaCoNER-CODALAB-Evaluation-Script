# PharmaCoNER-CODALAB-Evaluation-Script

## Digital Object Identifier (DOI)


## Introduction

This script is distributed as apart of the Pharmacological Substances, Compounds 
and proteins and Named Entity Recognition (PharmaCoNER) task. It is slightly based 
on the evaluation script from the i2b2 2014 Cardiac Risk and Personal Health-care 
Information (PHI) tasks. It is intended to be used via command line:

<pre>
$> python3 evaluate.py input output
</pre>

It produces Precision, Recall and F1 (P/R/F1) measures for both subtracks.



## Prerequisites

This software requires to have Python 3 installed on your system.


## Directory structure

<pre>
input/
This directory contains the gold standard files and the systems submission files (in this
distribution we include the gold set). Gold standard files must be placed under 
the `ref` directory and system files under the `res` directory. The `ref` directory 
contains two subdirectories with the files for `subtask1` and `subtaks2`. The `res` 
directory can contain one subdirectory with the files for `subtask1` or `subtaks2`. 
Files in the previous directories must be in the appropriate format: `.ann` 
and `subtask1` for `tsv` for `subtask2`. 


output/
This directory where the script outputs the results for the run.
</pre> 


## Usage
-----


the command line is:

<pre>
usage: evaluate.py input_folder/ output_folder/
</pre>


## Contact

Siamak Barzegar (siamak.barzegar@bsc.es)



## License

Copyright (c) 2019 Secretaría de Estado para el Avance Digital (SEAD)

Permission is hereby granted, free of charge, to any person obtaining a 
copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom the 
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included 
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS 
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN 
THE SOFTWARE.

