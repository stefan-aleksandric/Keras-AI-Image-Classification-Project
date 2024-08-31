# Keras-AiImageClassificationModel with NASNetMobile
This project uses the NASNetMobile model using Keras and Python for flower image classification. Transfer learning is applied for faster and more efficient training.

  Dataset: Loading and augmenting data from dataset that is uploaded to Google Drive.
  
  Model: Utilizing NASNetMobile without the top layer (include_top=False) and adding custom layers.

  Training:
  
    Freezing all base model layers except the last 20 for Fine-Tunning of the model.
    Compiling with the SGD optimizer.
    Implemented Early Stopping, Droput, Pooling, Conv2D, GridSearch , Skip connections...
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
    
    PDF file with summary of training,modeling and steps that were taken during the project.
