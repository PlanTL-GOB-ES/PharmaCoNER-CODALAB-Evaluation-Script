# PharmaCoNER-CODALAB-Evaluation-Script

## Digital Object Identifier (DOI)


## Introduction
------------

Efficient access to mentions of drugs, medications and chemical entities is a pressing need shared by biomedical researchers, clinicians and pharma industry. The recognition of pharmaceutical drugs and chemical entities is a critical step required for the subsequent detection of relations of chemicals with other biomedically relevant entities.

The critical importance of chemical and drug name recognition motivated several-shared tasks in the past, such as the CHEMDNER tracks or the i2b2 medication challenge. However, currently, most of the BioNLP, as well as clinical NLP research, is being done on English documents, and only a few tasks have been carried out on non-English texts or were multilingual tracks. Nonetheless, it is important to note that there is also a considerable amount of biomedically relevant content published in other languages than English and particularly clinical texts are entirely written in the native language of each country, with a few exceptions.

Following the outline of previous chemical and drug NER efforts, in particular, the BioCreative CHEMDNER tracks, we organize the first task on chemical and drug mention recognition from Spanish medical texts, namely from a corpus of Spanish clinical case studies. Thus, this task will address the automatic extraction of chemical, drug, gene/protein mentions from clinical case studies written in Spanish. The main aim is to promote the development of named entity recognition tools of practical relevance, that is chemical and drug mentions in non-English content, determining the current-state-of-the-art, identifying challenges and comparing the strategies and results to those published for English data.

For this task, we have prepared a manually classified collection of clinical case sections derived from Open access Spanish medical publications, named the Spanish Clinical Case Corpus (SPACCC). The corpus contains a total of 1000 clinical cases / 396,988 words. It is noteworthy to say that this kind of narrative shows properties of both, the biomedical and medical literature as well as clinical records.


These scripts are distributed as apart of the Pharmacological Substances, Compounds 
and proteins and Named Entity Recognition (PharmaCoNER) task. It is slightly based 
on the evaluation script from the i2b2 2014 Cardiac Risk and Personal Health-care 
Information (PHI) tasks. 

PharmaCoNER Website:
temu.bsc.es/PharmaCoNER(http://temu.bsc.es/pharmaconer/)


## Prerequisites
-------------

This software requires to have Python 3 installed on your system.


## Directory structure
-------------------

<pre>
Subtask1/
NER offset and entity classification.

Subtask2/
Concept indexing.
</pre> 


## Contact
------

Siamak Barzegar (siamak.barzegar@bsc.es)



## License
-------

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

