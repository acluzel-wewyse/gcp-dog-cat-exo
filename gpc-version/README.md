# Transfer Learning Class

The goal of this class is to show the potential of transfer learning, as well as its cost in time and processing power.
For this class we are using the dog-vs-cat dataset from Kaggle. The dataset should be in a GCP bucket dog-vs-cat-arnaud-test.

## Files included

This folder includes:

* __import_data.ipynb__: used to import the desired data from the GCP bucket to the folder

* __training_data__: includes 1500 images of dogs and 1500 images of cat, imported with import_data.ipynb

* __validation_data__: includes 500 images of dogs and 500 images of cat, imported with import_data.ipynb

* __test_data__: includes 500 images of dogs and 500 images of cat, imported with import_data.ipynb

* __model_evaluation_utils.py__: useful functions to evaluate models

* __transfer-learning.ipynb__: main notebook used for the class

* __cats_dogs_tlearn_basic_cnn.h5__: model saved from transfer-learning.ipynb

* __cats_dogs_tlearn_finetune_img_aug_cnn.h5__: model saved from transfer-learning.ipynb

* __cats_dogs_tlearn_img_aug_cnn.h5__: model saved from transfer-learning.ipynb

If the folders training_data, validation_data and/or test_data are missing, please run import_data.ipynb

The files cats_dogs_tlearn_basic_cnn.h5, cats_dogs_tlearn_finetune_img_aug_cnn.h5 and cats_dogs_tlearn_img_aug_cnn.h5 are **NOT** necessary to run transfer-learning.ipynb. These files are present in case the connexion breaks during a training stopping the user from finishing it.

## Library necessary

To run the notebook transfer-learning.ipynb, the following library need to be installed on the working environement.
I recomend using conda install instead of pip as anaconda will provide you with more info or solve environement issues.

* __tensorflow__
* __keras__
* __numpy__
* __pandas__
* __glob__
* __matplotlib__

