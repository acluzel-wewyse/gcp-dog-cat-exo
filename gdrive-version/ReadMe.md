# Transfer Learning Class - Gdrive Version

The goal of this class is to use Google Collab to show the potential of transfer learning.
For this class we are using the dog-vs-cat dataset from Kaggle. The shortened version of the dataset 'small-dog-cat.zip'
should be in the Wewyse gdrive folder.

## Setup Google Colab

### Getting a Notebook with GPU

To setup the notebook for the class open it on Google Colab and make sure your notebook is using a GPU.
To verify if you are using a GPU go to Runtime -> Change runtime type -> Hardware accelerator -> GPU

### Getting the Data

You also need to make sure that the Lab Wewyse folder is shared with you.
In the class you will fetch data in your google drive,
thus you need to make sure the Wewyse folder with the data is shared with you.

### Getting TensorFlow 2.0.0

Finally, to run the notebook you will need to install TensorFlow 2.0.0.
At the time this ReadMe is written TensorFlow 2.0.0 is not the default starting TensorFlow version of Google Colab's notebooks.
Once TensorFlow 2.0.0 is installed you will need to restart your Runtime so your notebook use the right version of TensorFlow.

Also Google Colab doesn't keep files imported on the instance once once the instance is closed.
You will therefore need to change TensorFlow version every time you'll start the notebook.

