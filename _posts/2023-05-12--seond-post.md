# Create a system to recongnize  bird
**From the  first class of fastai course, I learn a bit about how to establish a system to recognize bird**
There are three main steps:

**First,Download images of birds and known birds,in this stepl, we need to install a library called "duckduckgo_search".**
**From this library,we can get all the images that we want.**

**Second,train our model.In this step, we need a dataloader to contain a trainning set and a validation set.** 
**In addition,the Fine-tuning is a good method to adjust a little bit of the pre-trained model,so that the model can learn to recognise our test images.**
**when we train our model,we can creat our `learner` and fine-tune it,then we can generate a table like that**

| epoch | train_loss | valid_loss | error rate | time |
|-|-|-|-|-|
|   0   |  1.235733  |  0.21541   |  0.087302  |00:05 | 
 
Third step is to use our model to test the images that I have downloaded before.
With this method, we can establish our model to test many things rather than the birds.


![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)


