# logistic-regression-fromScratch
## A binary classification model built from scratch

Dogs vs Cats binary classifier...  A logistic regression built from scratch

This repository has two independently working files ... (You just need to run logisticregression file to run the project)
imagesdatatocsv -  this file converts all the images inside directory to image array using PIL and converts it to np array 
                  and hence stores in a csv file using pandas
 logistic regression - this is the main file which loads the images into array and then perform logistic regression in that... 
                    functions used - forward propagation (sigmoid activation) , cost function , backward propagation
                    
 Dataset used - Dogs vs Cats classifier (KAGGLE) https://www.kaggle.com/shaunthesheep/microsoft-catsvsdogs-dataset

The accuracy is not that great... since we use logistic regression (single layer) for such complicated data... 
and efficiency is also not that great since we are loading like 20,000+ images from directory ... but this is my first project I will surely work on that... 


