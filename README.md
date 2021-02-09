# Facial_Emotion_Recognition_Elearning
Facial Emotion Recognition in E-Learning: 
The main idea of this paper is to improve and enhance the quality of e-learning by detecting and monitoring students' emotions and providing quick feedback to teachers.  Emotions such as happiness, sadness, anger, disgust, fear, surprise and neutral are evaluated in this research. Artificial neural networks are used to identify and classify the different emotions in order to evaluate the level of understanding in the e-learning classes attended. Finally, the emotion artificial intelligence system provides feedback (in the form of a histogram plot) to the teacher about the most frequently occurring emotion. The teacher can then adjust the teaching strategy accordingly. By continuously receiving feedback on the current level of learning, the teacher can improve the learning performance. 

# Getting Started

The following instructions will get the model running 

First, download the publicly available FER-2013 Dataset

Then run the preprocessing.py file. After running fadataX.npy and flabels.npy files are generated (these file makes it easier for later)

Run the fertrain.py file (its recommended to us GPU, CPU takes way too long). This then creates modXtest.npy, modytest,npy, fer.json, fer.h5 file. Fruthermore a summary history of the accuracy and loss are plotted and saved as .png

Run confmatrix.py file to get the confusion matrix. The most confused expressions are plotted and saved as .png
