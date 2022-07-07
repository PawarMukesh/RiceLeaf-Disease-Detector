# Rice-Leaf-Disease-Detection

## INTRODUCTION
The rice leaf suffers from several bacterial, viral, or fungal diseases and these diseases reduce rice production significantly. To sustain rice demand for a vast population globally.The rice leaves related diseases often pose threats to the sustainable production of rice affecting many farmers around the world. Early diagnosis and appropriate remedy of the rice leaf infection is crucial in facilitating healthy growth of the rice plants to ensure adequate supply and food security to the rapidly increasing population.

### Rice Leaf Disease:
![image](https://user-images.githubusercontent.com/101791322/177773023-a8114cb6-c1c4-497b-b51f-de9baef4e8d5.png)

### DATA SUMMARY
This dataset contains 120 jpg images of disease infected rice leaves. The images are grouped into 3 classes based on the type of disease. There are 40 images in each class.

### Classes

* Leaf smut
* Brown spot
* Bacterial leaf blight

### WE HAVE DEVICE THE PROJECT INTO MULTIPLE STEPS:
* Importing library
* Loading data
* Preparing data
* Data Processing 
* Model building
* Training
* Evaluation
* Testing



### LODING DATA / PREPARING DATA
•	Make a subset of data into three parts train, test, and validation with the help of split folder library.

### DATA PROCESSING
•	In this step generate the batches of training and validation and pre-process the images

### PLOTTING TRAINING IMAGES:
![image](https://user-images.githubusercontent.com/101791322/177773523-fbb6bcbe-81ff-4805-a34d-b655083de8de.png)

### MODEL BUILDING

* In this step we create CNN model architecture in that three types of layers convolution layer, pooling layer, 
And fully connected layer are added.
* Plotting a graphical representation of model
*	Get the summary of model
*	Compile model
*	Then the last train the model 
*	After training validation accuracy is 91.67% and accuracy is 84.38%.
*	Save the model

### MODEL EVALUATION:
•	Here the loss is 0.53 and the accuracy of model is 0.9166 means 91.66%

### MODEL TESTING:
In this step we are create a function to test multiple images from test data. 

RESULT:
![image](https://user-images.githubusercontent.com/101791322/177774011-ba9942b4-ab73-40cf-a3db-8c5db75a64df.png)

 



