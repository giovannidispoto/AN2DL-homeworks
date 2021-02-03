# Artificial Neural Networks and Deep Learning Homeworks

<b>Authors:</b> [Giovanni Dispoto](https://github.com/giovannidispoto), [Matteo Sacco](https://github.com/matte-esse) 

### Image classification

Competition available on [Kaggle](https://www.kaggle.com/c/artificial-neural-networks-and-deep-learning-2020/overview).
We have created a CNN that discriminate between images depending on the following cases:
1) All the people in the image are wearing a mask
2) No person in the image is wearing a mask
3) Someone in the image is not wearing a mask. In the following 3 examples of image from the training belonging to the three cases


There are 2 models: One based on Transfer Learning on VGG19 model trained on ImageNet Dataset and a model trained from scratch, reaching maximum accuracy on 

### Image Segmentation

[ACRE](https://metricsproject.eu/agri-food/acre-competition/) is the Agri-food Competition for Robot Evaluation, part of the METRICS project funded by the European Union’s Horizon 2020 research and innovation program under grant agreement No 871252. Autonomous robots compete to demonstrate their ability to perform agricultural tasks (such as removing weeds or surveying crops down to individual-plant resolution). At field campaigns, participants collect data that are then made available for online competitions (Cascade Campaigns) like the one you are seeing. For more information about ACRE and METRICS visit the official website.

There a 3 model in notebooks:
* Model based semplified version of U-Net, without Skip Connection
* Model based on U-Net
* Model based on FPN

### Visual Question Answring
Competition available on [Kaggle](https://www.kaggle.com/c/anndl-2020-vqa). <br>
We have created a model with a pre-trained Xception CNN + RNN with LSTMs as described in the paper [VQA: Visual Question Answering](https://arxiv.org/pdf/1505.00468v6.pdf) in order to answer specific question on images.

More information about models are present in the pdf file ,in each directory.





