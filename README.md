# Artificial Neural Network and Deep Learning Homeworks

### Image classification

Competition available on [Kaggle](https://www.kaggle.com/c/artificial-neural-networks-and-deep-learning-2020/overview).
We have created a CNN that discriminate between images depending on the following cases:
1) All the people in the image are wearing a mask
2) No person in the image is wearing a mask
3) Someone in the image is not wearing a mask. In the following 3 examples of image from the training belonging to the three cases

<img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F3311561%2Fbbb25e67374ea55c2f15f575b2989746%2F11056.jpg?generation=1604834938309207&alt=media"  width="300"/>
<img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F3311561%2Fef05c005aa712dae1fd71351f2c5b3f7%2F10405.jpg?generation=1604835094952941&alt=media"  width="300"/>
<img src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F3311561%2F2a987afcb01c2f48e296c30924ad51a7%2F11172.jpg?generation=1604835052572395&alt=media"  width="300"/>

There are 2 models: One based on Transfer Learning on VGG19 model trained on ImageNet Dataset and a model trained from scratch, reaching maximum accuracy on test set of 0.895
