# Image_Classifier_Model_Using_CNN

* Objective: Accurately classify handwritten digits using a deep learning model.

* Dataset: Uses the MNIST dataset (handwritten digits 0-9).

* Preprocessing: Converts images to grayscale, resizes them to 28x28, normalizes pixel values, and reshapes for CNN input.

* CNN Model:

    Two convolutional layers (Conv2D) with ReLU activation.

    MaxPooling layers to reduce dimensions.

    Fully connected (Dense) layer for classification.

    Dropout layer to prevent overfitting.

* Training & Evaluation:

   Model trained using the Adam optimizer and categorical cross-entropy loss.

   Accuracy and loss tracked over multiple epochs.

* Prediction:

   Custom image input supported (upload a handwritten digit).

   Image preprocessed and classified using the trained CNN.

   Prediction displayed with visualization.
