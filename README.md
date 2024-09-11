# Keras-AiImageClassificationModel with NASNetMobile
This project uses the NASNetMobile model with Keras and Python for flower image classification. Transfer learning is applied for faster and more efficient training.

  Dataset: Loading and augmenting data from dataset that is uploaded to Google Drive.
  Link: https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz
  
  Model: Utilizing NASNetMobile without top layers and adding custom layers for fine tunning of the model.

  Training:

    Normalization and agumentation of photos from dataset.
    Freezing all base model layers except the last 20 for the Fine-Tunning of the model.
    Compiling with the SGD optimizer.
    Implemented Early Stopping, Droput, Pooling, Conv2D, Skip connections...
    Added custom GridSearch function for trying out different hyperparameters.
    
  Evaluation: 
  
    The model was trained and evaluated on the validation set.
    Code for trying out various photos from internet and batches of photos from dataset is implemented.
    
  How to Run:
  
    Load the dataset to the specified path.
    Execute the code to train the model.
    Monitor loss and accuracy metrics during training.

  Context:
  
    Jupyter notebook is included.
    
    PDF version of the same notebook is included.
    
    PDF file with summary of training, modeling and steps that were taken during the project.
