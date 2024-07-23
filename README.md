# Google-Satellite-Image-Classification-using--deep-learning

This project focuses on aerial scene classification using a deep learning model trained on an image dataset. The goal is to identify and categorize different types of landscapes, regions, or objects visible from an aerial perspective. Such a model has applications in land-use planning, environmental monitoring, and urban development analysis.

## Project Overview

-   **Data**: The dataset consists of 8267 images for training and 1800 images for validation, categorized into 30 different classes representing various aerial scenes.
-   **Model**: A convolutional neural network (CNN) is trained to learn and classify the features of different aerial scenes accurately.
-   **Metrics**: The model's performance is evaluated using accuracy, precision, recall, and F1 score.

## Key Results

-   **Accuracy**: 84.34%
-   **Precision**: 83.98%
-   **Recall**: 84.12%
-   **F1 Score**: 84.16%

## Notebook Contents

1.  **Data Loading and Preprocessing**:
    
    -   Loading the aerial image dataset from the specified directory.
    -   Preprocessing the images for training and validation.
2.  **Model Training**:
    
    -   Building the CNN model using TensorFlow and Keras.
    -   Training the model over 10 epochs.
    -   Tracking the loss and accuracy during training.
3.  **Model Evaluation**:
    
    -   Making predictions on the validation set.
    -   Calculating accuracy, precision, recall, and F1 score for the model.
4.  **Results and Conclusions**:
    
    -   Displaying the final evaluation metrics.
    -   Discussing the model’s performance and potential improvements.

## Use Cases

-   **Land-Use Planning**: Classifying different types of land use from aerial images for better planning and management.
-   **Environmental Monitoring**: Identifying changes in landscapes to monitor environmental conditions and changes over time.
-   **Urban Development Analysis**: Analyzing urban areas and infrastructure development from aerial imagery.

## How to Use

1.  Clone the repository:
    
    bash
    
    Copy code
    
    `git clone https://github.com/yourusername/your-repo-name.git` 
    
2.  Install the required dependencies:
    
    bash
    
    Copy code
    
    `pip install -r requirements.txt` 
    
3.  Run the Jupyter notebook:
    
    bash
    
    Copy code
    
    `jupyter notebook Project2.ipynb` 
    

## Requirements

-   Python 3.x
-   TensorFlow
-   Keras
-   scikit-learn
-   Jupyter Notebook

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
