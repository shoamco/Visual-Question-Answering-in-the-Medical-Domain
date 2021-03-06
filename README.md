# VQA of CT and MRI in deep-learning

## Visual Question Answering in the Medical Domain - Identifying  MRI and CT images using  convolutional neural network 

  <img width="460" height="300" src="https://github.com/shoamco/VQA-of-CT-and-MRI-in-deep-learning/blob/master/docs/pic/logo.jpg">

# About the project
### this project is part of the challenge of ImageCLEF-[ImageCLEF-VQA-Med](https://www.imageclef.org/2018/VQA-Med) .

Visual Question Answering is a new and exciting problem that combines natural language processing and computer vision techniques.

Given a medical image accompanied with a clinically relevant question, participating systems are tasked with answering the question based on the visual image content.


The general way to solve this kind of problem is by finding identical features between the image that the user inserts and the rest of the images in the training set database, as well identifying the main words in the question statement and comparing them to other similar questions in the training set database.

In our solution, we worked only on questions whose answers contained MRI or CT words.

We tried to identify the type of image and to return the type of the image (MRI or CT) as an answer that of course would be a part of the original answer.

The answer file we provide will be compared with the original answer file in the Evaluation

the Evaluation is conducted based on the following three metrics: BLEU, WBSS, and CBSS
 
# Staff:
* [hodaya marciano](https://github.com/hodayamar)
* [shoam cohen](https://github.com/shoamco/)
