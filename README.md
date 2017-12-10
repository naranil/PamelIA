# PamelIA
Data Science project to explore the integration of IA in the medical field

## Création du model
Launch this file : train_tensorflow.py
It will create two files (best and final) with the model.

## App
predict_tensorflow.py {NOM_MODEL.h5} {NOM_PHOTO}

## Project tree
PamelIA
 * [data](IASC/data)<br/>
   Data to train the model
   * [train](IASC/data/train)<br/>
     *[benign](IASC/data/train/benign)<br/>
     Pictures of your first category<br/>
     *[malignant](IASC/data/train/malignant)<br/>
     Pictures of your second category<br/>
     
   Data to validate the training
   * [valid](IASC/data/valid)<br/>
     *[benign](IASC/data/train/benign)<br/>
     Pictures of your first category<br/>
     *[malignant](IASC/data/train/malignant)<br/>
     Pictures of your second category<br/>
     
 Data to test the model
 * [test](IASC/test)


