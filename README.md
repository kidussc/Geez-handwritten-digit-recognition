# Geez-handwritten-digit-recognition

Handwritten Ge'ez Digits Recognition-machine learning model recognizing handwritten Ge'ez digits into the 20 different single digits of the Ge'ez / Amharic / Ethiopic Digits. 
Test out the model here https://geezhandwrittendigit.web.app/.
# Dataset
The dataset used for training consists of 32,319 images of handwritten Ge'ez digits, divided into 20 classes. The dataset has been curated to ensure high quality and balance.

# Data Preprocessing
Before training the model, the dataset underwent the following preprocessing steps:

Resizing: All images were resized to a standard size of 32x32 pixels to ensure consistency.
Pixel Normalization: The pixel values were normalized to a range of [0, 1]. All non-zero pixels were set to 1, simplifying the input for the model.
# Model Training
The model was trained using TensorFlow and Keras

Training Accuracy: 99.4%
Test Accuracy: 99.1%
These accuracy scores demonstrate the effectiveness of the model in accurately classifying handwritten Ge'ez digits.

# Usage

Preprocess the input image by resizing it to 32x32 pixels, then change non-zero pixels to 255. Finally, applying pixel normalization.
Feed the preprocessed image into the model for prediction.
The model will output the predicted class label for the input digit. Use the label_mapping.json file to get the predicted number.
# Dataset Split
The dataset was split into training and testing sets using an 85% - 15% ratio.

# Authors
Kidus Sisay
