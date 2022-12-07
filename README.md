  High level description/presentation of the project
  
- Requirements to run your Python code (libraries, etc)
    Our Python ipynb files in the source code folder has all the neccesary libraries loaded. So to run the ipynb files download and open those files into a pytorch       running environments such as google colab, kaggle notebooks. Now you just need to execute the cell in order to fetch those libraries. Execute     cell by cell in order  so that no cell is missed while execution. However, please be mindful of the dataset path that needs to be set to the dataset either downloaded into your local drive  path or google drive path. 
    
- Instruction on how to train/validate your model
As two of our datasets are already split to train test and validation sets you just to set paths for each folder in the dataset. However, in case of freiburg dataset you have specifically mention the test split and validation split so that the dataset can be divided. Further, define a model from pytorch library and run it. Now create a train function to train the defined model on the dataset. Next, define the epochs, optimizer and loss function to call the train function and train the model. 

- Instructions on how to run the pre-trained model on the provided sample test dataset
The Sample dataset consists of 100 images of each of 3 datasets. So you can choose any dataset and run it. To run it, please load the model using torch.load("modelname.pt") and next execute model.eval(). Now you can create a training loop with the test dataset and run the model for testing.

How to Obtain the datasets: Please click the below links for downloading datasets
  Freiburg Groceries Dataset: https://drive.google.com/drive/folders/1ObcWjcKU-7u3WgxRTRBSprqHkPxA7BO6?usp=share_link
  Grocery Store Dataset: https://drive.google.com/drive/folders/1I4VHgdysyN5jxLHYVRtneTPmvQa5hOB3?usp=share_link
  Vegetable Images Dataset: https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset
