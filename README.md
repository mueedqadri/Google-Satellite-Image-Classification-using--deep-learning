# Google-Satellite-Image-Classification-using--deep-learning
This project involves developing an advanced system to optimize electricity procurement from multiple sources while minimizing the daily electricity bill. The project addresses the complexities of predicting electricity demand and source output and formulating an optimization problem with various constraints.

#### Key Features and Achievements:

1.  **Optimization Algorithm**:
    
    -   Developed an algorithm to optimize electricity procurement from different sources, considering constraints on the maximum electricity usage from each source.
    -   The objective was to minimize the daily electricity bill by determining the optimal bid quantities and prices for each hour.
2.  **Neural Network Model**:
    
    -   Implemented a neural network model using TensorFlow and Keras to predict daily electricity demand and the output of various sources.
    -   Extracted and engineered features from historical data to train the model, achieving high accuracy in predictions.
3.  **Feature Engineering and Machine Learning**:
    
    -   Processed historical data to extract relevant features for the prediction model.
    -   Utilized machine learning techniques, including clustering and regression, to solve the optimization problem with bid quantities and prices as decision variables.
4.  **Technology Stack**:
    
    -   Employed Python libraries such as Pandas for data manipulation, scikit-learn for machine learning, and OR-Tools for solving linear programming problems.
    -   Integrated TensorFlow and Keras for building and training the neural network model.

#### Technical Details:

-   **Data Preprocessing**:
    
    -   Collected and cleaned data on electricity demand, solar output, and market prices.
    -   Normalized and transformed data for input into the neural network model.
-   **Model Training**:
    
    -   Trained a VGG19-based neural network model with customized layers for enhanced feature extraction and prediction accuracy.
    -   Used ImageDataGenerator for data augmentation and flow_from_directory for efficient data loading.
-   **Optimization Solution**:
    
    -   Formulated a linear programming problem to minimize costs while meeting demand constraints and managing battery storage.
    -   Solved the optimization problem using OR-Tools, ensuring efficient and optimal resource allocation.
-   **Evaluation**:
    
    -   Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1 score.
    -   Achieved significant improvements in prediction accuracy and cost savings.

This project demonstrates a comprehensive approach to managing electricity demand and procurement, leveraging advanced machine learning techniques and optimization algorithms to deliver tangible benefits in cost reduction and resource efficiency.
