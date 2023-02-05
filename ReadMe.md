This repository contains all code and files used to train a negation detection classifier. The project was carried out by Rishvik, Carol  and Apostolos for our course Applied Text Mining in P3 of the 2022-2023 academic year.

Task: Negation cue detection 

Abstract: In this paper, we present a system using two different methods in order to detect negation words in a text. Through the first sections of the paper, we address the task of annotation. Furthermore, we train a (CRF) and an (SVM) model on morphological lexical and syntactic features. After training, we compare the results of CRF and SVM using a simple baseline model we built. Moreover, we make an error analysis summing it all up in the last section where we come up with some conclusions about the research we have done.

Algorithms used: 
    CRF Conditional Random Field Model
    SVM Support vector machine Model

Data:
Data sets used in this project are listed below, all the datasets were provided by our techers. 

Training data: SEM-2012-SharedTask-CD-SCO-training-simple.txt
Development data: SEM-2012-SharedTask-CD-SCO-dev-simple.txt
Test data 1 : SEM-2012-SharedTask-CD-SCO-test-cardboard.txt
test data 2 : SEM-2012-SharedTask-CD-SCO-test-circle-.txt

We have merged our two datasets into one big test data set.


Code:
The following file contains our code:

Baseline_mode: consist of code for our baseline model's implementation
SVM_model : code for our SVM model's implementation
CRF_model : code for our CRF model's implementation


Other files:
3 annotation files 
    Rishvik_annotations
    Apostolos_Syrris_annotations
    Carol_Rameder_saved
each file contains 12 annotation files.

******


