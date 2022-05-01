# Moodify

## Description

Have you ever experienced that the instagram posts visible to you are completely unrelated to what you wanted to see ? Well, not anymore.
Moodify will classify your insta feed according to your current mood, which will make your feed more engrossing and relatable. We will use Instagram API for gathering the feed and apply our model to select relevant posts. We plan to build a ML model which will classify the posts based on their picture, caption, and top few comments to predict which mood is more likely to relate with this post. 
Initially we will learn a CNN based model for the image part and a RNN based model for the textual part. Then we will combine their outputs to predict a common metric and classify the outputs in "happy", "funny", "motivational" etc.
We will only be working on those posts with a single image (in case of multiple images we will select the first one). Later, if time permits, we may also build a mobile application for the same.

## Checkpoints

- Learning basics of CNN and RNN
- Understanding MetaForDevelopers API offered by instagram
- Building the CNN model for image classification
- Implementing RNN model for textual data
- Combining both the models to get the final output, and hyper parameter tuning for achieving better results 

## Weekly Plan

### Week 1
Reading material for this week \-
- [Python tutorial](https://www.w3schools.com/python/) (you can leave file handling onwards part)
- [Basics of Neural Network](https://www.analyticsvidhya.com/blog/2021/03/basics-of-neural-network/)
- [Details of Neural Network](https://www.analyticsvidhya.com/blog/2021/05/beginners-guide-to-artificial-neural-network/)
- [NN with implementation](https://towardsdatascience.com/neural-networks-for-beginners-by-beginners-6bfc002e13a2) (You can skip the CNN part for now)
- [Pytorch NN](https://curiousily.com/posts/build-your-first-neural-network-with-pytorch/)
- [Another Pytorch NN](https://towardsdatascience.com/how-to-code-a-simple-neural-network-in-pytorch-for-absolute-beginners-8f5209c50fdd)

### Week 2
Reading material for this week \-
- [Understanding CNN](https://www.analyticsvidhya.com/blog/2021/05/convolutional-neural-networks-cnn/)
- [CNN Implementation in PyTorch](https://medium.com/thecyphy/train-cnn-model-with-pytorch-21dafb918f48)
