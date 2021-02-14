# Image-Captioning-Project.
Final Project for 1st Course in the Advanced Machine Learning Specialization. The Project Uses word embedding with LSTM from RNN along with Image embedding using final layers of InceptionV3 pretrained model from CNN. To Caption Images.

The model usses RNN text generator. It uses image features as an initial state for RNN instead of zeros.

we pass the image feature vector to the RNN and then feed the label to LSTM to Predict the next token. 
