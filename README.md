# iris classifier

## project overview

this project was created as part of the ai foundation course.

the aim is to develop a machine learning model that can classify iris flowers into three species:

- iris setosa
- iris versicolor
- iris virginica

## how the model works

the project uses python and the scikit-learn library.

the iris dataset contains measurements of flower petals and sepals.

the dataset is divided into training data (80%) and testing data (20%).

a random forest classifier is trained to predict the flower species.

the model is evaluated using accuracy and a confusion matrix.

## project structure

- notebooks/iris_model.ipynb - jupyter notebook containing the model code.
- src/train.py - python script used to train the model.
- outputs/confusion_matrix.png - visual representation of predictions.
- outputs/model.joblib - saved trained machine learning model.
- tests/ - folder for testing.
- requirements.txt - required python libraries.

## how to run the project

1. install python.
2. install the required packages using:

   pip install -r requirements.txt

3. run the training script using:

   python src/train.py

4. check the outputs folder for the trained model and confusion matrix.

## conclusion

this project demonstrates how machine learning can be used to classify iris flowers based on their measurements.
