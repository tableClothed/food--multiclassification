#  Food Multiclassification 🥗

The classificier predicts an array of labels for a single image of food.
Trained on images of 101 different dishes, such as apple pie, greek salad, sushi, etc.

Using:
- Tensorflow 1.15
- Python 3.7
- Sklearn
- Pandas
- OpenCV

Predicting models:
- Xception
- ResNet50
- DenseNet121

-------------------------

#### The labels:
- healthy
- junks
- desserts
- appetizers
- mains
- soups
- carbs
- proteins
- fats
- meat

![img](https://github.com/tableClothed/food--multiclassification/blob/master/data/example.png)

--------------
### Usage:
Create a folder. Then using your console write `git clone https://github.com/tableClothed/food--multiclassification.git`.

When the repo finishes cloning, enter the *food--multiclassification* folder. 

Using your Anaconda console in here use `jupyter anaconda` command.

In your working tree click on *models.ipynb* and train whichever predicting model you like (Xception, ResNet50 or DenseNet121).

After that enter the *models.ipynb* file, find `model = tensorflow.kerasmodels.load_model({MODEL})` and in place of *{MODEL}* insert the name of model, you'd like to use for making predictions.

If you wish to add more testing images, you can paste them to *'data/test'* folder.

