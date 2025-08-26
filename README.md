# Email_Spam_Classifier

### **Enhanced README Descriptions for GitHub**

#### **1. Digit Recognition Model**

This project presents a **Digit Recognition Model** utilizing a Convolutional Neural Network (CNN) built with **TensorFlow** and **Keras** to classify handwritten digits. The model is trained on the MNIST dataset and is capable of recognizing digits from 0 to 9.

**Key Features & Technologies:**

* **Convolutional Neural Network (CNN):** The core of the model is a CNN, which is highly effective for image classification tasks.
* **TensorFlow & Keras:** These powerful deep learning libraries are used to build, train, and manage the model.
* **OpenCV (`cv2`):** The project includes an interactive drawing canvas created with `OpenCV`, allowing users to draw a digit in real time.
* **Real-time Prediction:** The application can predict the drawn digit in real-time by pressing the `spacebar`.
* **Data Preprocessing:** The drawn digit is resized to a 28x28 pixel grayscale image and normalized before being fed into the model for prediction.

**How to Use:**

To interact with the model, run the Jupyter Notebook. The user interface provides simple controls:
* **Spacebar:** Press to get a real-time prediction of your drawn digit.
* **'c'**: Press to clear the canvas.
* **ESC**: Press to exit the application window.

***
