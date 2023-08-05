# 3D-chair-project
Using deep learning to discern a 3d chair model photo from a real chair photo.

## THE GOAL
The goal of this project was to see whether deep learning could be used to differentiate between 3D and real photos. 
In another way of thinking, I was wondering whether machines could detect 3D's weaknesses/inability to replicate reality. 

Many 3D artists strive to replicate reality, and many CGI videos have deceived people in the past. For example fake UFO/ghost sightings.
Deep learning could essentially rate artists abilty to replicate reality, or be used as a way to identify fake videos. 
As someone who has dabbled in 3D art, I want to continue on this path and see whether artifical intelligence could be used to make life easier for artists and expand their possibilities. 

## What I learnt
My explanation and process of creation can be found in '3d-chair-or-real-chair.ipynb', or alternatively on Kaggle at: https://www.kaggle.com/code/harule/3d-chair-or-real-chair

In terms of the basics of deep learning:
- How to split data into training and validation sets to build the model. (There wasn't a test dataset due to limited time, so it's unknown whether the model overfits/underfits, we only tested one image with typically above 80% accuracy)
- Basic underfitting/overfitting understanding
- Neural network basics, weights, biases.. how visual neural networks work.

With other things:
- fastai Documentation
- Handling images
- Using libraries (first time using ddg and fastai, and also learnt more about mat.plot.lib)

And perhaps most importantly I learnt the possibilities of deep learning. Through even just a bit of research I realised that a lot can be done. The potential is wide, there are still many things left undone, there are competitions on Kaggle etc. 
In the future I want to use deep learning on actual 3D models. 

## In conclusion
The results and conclusion can be found on '3d-chair-or-real-chair.ipynb' or the Kaggle, but I would like to provide proof of limitations I faced.
![image](https://github.com/Daruler24/3D-chair-project/assets/136204110/6d2da369-9705-439a-8421-725ba5648ed1)
![image](https://github.com/Daruler24/3D-chair-project/assets/136204110/86d886ea-fb8e-4e85-b347-e2817dc8a772)

As can be seen 3d artists striving for realism can deceive even humans, and machine neural network's have yet to surpass biological ones, so this project still has work to do to be able to discern all 3d manufactured images from real ones. 
There were many struggles with libraries and functions however by reading official documentation carefully, you can typically achieve the results you want. For example I was trying to extract the train_losses from the graph in order to plot them. But val_losses didn't exist. However there was a plot_losses function under learn.recorder that helped. Although it doesn't record in epochs but batches. 
