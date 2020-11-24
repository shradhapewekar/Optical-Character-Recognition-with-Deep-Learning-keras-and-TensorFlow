# Optical-Character-Recognition-with-Deep-Learning-keras-and-TensorFlow

The motivation of our project comes from the fact that a lot of people still prefer to write on physical papers - if handwritten documents are digitized and stored, we believe it will add a lot of value in the long term. Additionally, due to the recent pandemic (COVID-19) affecting people’s lives, people are encouraged to stay home and avoid physical interactions. This resulted in an increasing amount of people scanning and taking pictures of documents for uploading purposes.
Traditional OCR (Optical Character Recognition) yields very good results only on very specific use cases like converting printed Portable Document Format (PDF) documents to on-screen text. However, in general, it is still considered challenging for problems like handwritten documents.
Deep learning driven Neural Networks can be used to dramatically improve the accuracy of handwritten text recognition. In our project, we will be using Python as the programming language. We will be discussing how handwriting text recognition can be done using deep learning, keras, and TensorFlow

Dataset Description

1)	Mnist data set: This data set from keras is used for digit recognition. It consists of 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images.
2)	AZ-handwritten-alphabets-in-csv-format: This dataset is downloaded from Kaggle. It contains 26 folders (A-Z) containing handwritten images in size 28x28 pixels, each alphabet in each image is stored as Gray-level.
3)	Our own data set of lowercase a-z letters: We generated our own dataset of 1,200 lowercase characters using Google Images. JavaScript was used to gather the image URLs and a Python file used to download the images to a folder.
4)	Handwritten words: We have created our own dataset using our own handwritten words. We have used offline methods (input information is obtained through static information (images)) which involve recognizing text once it's written down.
