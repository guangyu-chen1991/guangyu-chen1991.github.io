# Create a system to recongnize  bird
From the  first class of fastai course, I learn a bit about how to establish a system to recognize bird
There are three main steps:
First,Download images of birds and known birds,in this stepl, we need to install a library called "duckduckgo_search".
From this library,we can get all the images that we want.
Second,train our model.In this step, we need a dataloader to contain a trainning set and a validation set. 
In addition,the Fine-tuning is a good method to adjust a little bit of the pre-trained model,so that the model can learn to recognise our test images.
