This repository contains all code and files used to train a negation detection classifier. The project was carried out by Rishvik, Carol  and Apostolos for our course Applied Text Mining in P3 of the 2022-2023 academic year.

Task: Negation cue detection 

Abstract: In this paper, we present a system using two different methods in order to detect negation words in a text. Through the first sections of the paper, we address the task of annotation. Furthermore, we train a (CRF) and an (SVM) model on morphological lexical and syntactic features. After training, we compare the results of CRF and SVM using a simple baseline model we built. Moreover, we make an error analysis summing it all up in the last section where we come up with some conclusions about the research we have done.

Algorithms used: 
    `CRF Conditional Random Field Model`
   ` SVM Support vector machine Model`

### Data:

Data sets used in this project are listed below, all the datasets were provided by our techers. 


training data: `SEM-2012-SharedTask-CD-SCO-training-simple.txt`

development data: `SEM-2012-SharedTask-CD-SCO-dev-simple.txt`

test data : `SEM-2012-SharedTask-CD-SCO-test-cardboard.txt`

test data : `SEM-2012-SharedTask-CD-SCO-test-circle-.txt`

We have merged our two datasets into one big test data set.


### Code:
The following file contains our code:

`Baseline_mode`: consist of code for our baseline model's implementation

`SVM_model` : code for our SVM model's implementation

`CRF_model` : code for our CRF model's implementation


### Other files:
3 annotation files 

    `Rishvik_annotations`
    
    `Apostolos_Syrris_annotations`
    
    `Carol_Rameder_saved``
    
each file contains 12 annotation files.

******

### Work distribution:
`Carol`: Corrected writing errors, and organized paragraphs
and sections. Wrote and implemented all (CRF model note-
book file from Github) the experiments for the CRF model
(5.3.2) including data preprocessing (5.1), feature extraction
and selection (5.2), experimental setup (5.4) and error analy-
sis (7.2). Wrote the Error Analysis for the Annotation task
(A2) (3, 3.2, 3.2.1) and Dataset description parts (4).

`Rishvik`: Worked on implementation of SVM model file (code
plus text), wrote results section of SVM in the result sec-
tion. Wrote introduction segment, in data section wrote and
described all the usefull features, worked on tables, inden-
tation and grammatical errors. Worked and wrote on the
error analysis part of SVM model as well, and compared the
results.

`Apostolos`: Worked on the implementation of the Baseline
model (notebook file from Github) and the data pre-processing.
Wrote and worked on the abstract , the conclusion, the pre-
vious work section, the annotation task and the types of
negation, and the methodology section including the base-
line model. Lastly compared the results .
