# Week-1
EcoSort AI -- A deep learning–based image classification project that uses CNNs to recognize and categorize waste, encouraging eco-friendly recycling practices.
Project Problem Statement
This project, titled EcoSort AI, focuses on developing an intelligent waste classification model
using Convolutional Neural Networks (CNNs). The system aims to automatically identify and
categorize waste images into six classes: cardboard, glass, metal, paper, plastic, and trash. By
integrating CNN-based deep learning techniques, the project promotes automation in waste
segregation processes and enhances recycling efficiency. The model will be trained using the
Garbage Classification Dataset from Kaggle and refined using Google Teachable Machine for
improved accuracy and adaptability.
The primary objective of EcoSort AI is to contribute to sustainable development by utilizing deep
learning for smarter waste management. The project aligns with the United Nations Sustainable
Development Goal 12 – Responsible Consumption and Production, encouraging eco-friendly
practices and reducing landfill waste through intelligent automation.
Dataset
Dataset Name: Garbage Classification Dataset
Source: Kaggle – A high-quality image dataset designed for waste classification and recycling
research.
This dataset contains thousands of labeled images categorized into six waste types: cardboard,
glass, metal, paper, plastic, and trash. Each image is pre-organized into folders, making it suitable
for CNN-based classification tasks. It provides an ideal foundation for developing AI-powered waste
segregation systems that support sustainable environmental practices.
Next Steps
 1. Collect and Prepare Dataset from Kaggle.
 2. Preprocess and organize images for training and validation.
 3. Train the CNN Model using Google Teachable Machine.
 4. Evaluate the Model’s Performance using accuracy metrics and confusion matrix.
 5. Build a Simple Web Interface using Python Streamlit for testing classifications.
 6. Test the Application with real-world images of waste materials.
 7. Deploy and Document the Complete Project.
    # Week-2
    Week 2 was all about model training, evaluating the model
    In Week 2, the focus was on training, testing, and validating the CNN model for the EcoSort AI project — a waste classification system built using Convolutional Neural Networks (CNNs) and Teachable Machine.
The objective was to verify that the model correctly identifies various types of waste images such as plastic, paper, metal, cardboard, biological, clothes, shoes, and trash, supporting sustainability and efficient waste management.
⚙️ Activities Performed

Model Training

The CNN model was trained using Google’s Teachable Machine on a custom waste dataset (sourced and refined from Kaggle).Each waste type was treated as a separate class to enhance classification accuracy.
The final trained model was exported as keras_model.h5 with corresponding labels in labels.txt.

Project Setup in VS Code
A structured project directory was created:

EcoSort_AI/
├── model/
│   ├── keras_model.h5
│   ├── labels.txt
│   └── test_image.jpg
├── src/
│   └── predict.py
├── ecosort-env/  (virtual environment)

The TensorFlow environment (ecosort-env) was configured successfully.Necessary libraries were installed: tensorflow, pillow, numpy, opencv-python, and streamlit.

Model Testing

The exported Keras model was loaded into the predict.py script.A single test image was passed through the model to evaluate predictions.The output displayed the predicted waste type along with a confidence score, proving successful model inference inside VS Code.

Debugging & Path Fixes

Issues related to file paths and model compatibility were resolved.Environment configuration was validated, and model execution logs were recorded.

🚀 Next Steps (Week 3 Preview)

In Week 3, the focus will be on:
*Integrating Jupyter Notebook for visualization and explanation.
*Testing with multiple images for each class.
*Plotting accuracy graphs and confusion matrices.
*completing the completed project and finally the PPT works
