# Human-Activity-Recognition-using-Accelerometer-and-CNN
With the accelerometer dataset, Human activities are analyzed and predicted using the CNN model.

Using the 2D Convolutional Neural Networks, the accelerometer dataset is trained in order to predict the human activities

1.Data Preprocessing

The dataset in .txt format is loaded into the program and processed to convert into a processable form. Further, it is converted into a dataframe which can be easily analyzed.

2.Balancing the Data

The data is an unbalanced one. It should be balanced in order to avoid bias. Then, the data is encoded using Label Encoder.

3.Standardization of Data

The data is standardized using Standard Scaler.

4.Creating Frame

With a function get_frames, frames are created from the dataset.

5.CNN Model

2D Convolutional Neural Networks are used to train the model and the accuracy of the results are analysed with confusion matrix and plots.
