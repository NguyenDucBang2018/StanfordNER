# StanfordNER
Stanford pre-trained model for Vietnamese Named Entity Recognition 

1. How to use

(i) Download StanfordNER library from here https://nlp.stanford.edu/software/stanford-ner-2018-02-27.zip

(ii) Add a text file in this folder with any sentence or paragraph you want (For example: sample.txt)

(iii) Open cmd and type the following command
java -mx600m -cp <drag_jar_file_directory_you_just_download_step_(i)> edu.stanford.nlp.ie.crf.CRFClassifier -loadClassifier ner-model.ser.gz -textFile sample.txt

2. License
This model is distributed with license same as StanfordNER library
