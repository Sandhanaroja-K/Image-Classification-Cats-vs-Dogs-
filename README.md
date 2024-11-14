# Image-Classification-Cats-vs-Dogs

### Project Overview

This project focuses on building an image classification model to distinguish between images of cats and dogs. The code uses machine learning algorithms, including Logistic Regression, Decision Tree, and Random Forest, to classify images into their respective categories. The project also includes hyperparameter tuning for optimizing the Random Forest model.

### Project Structure

- **Dataset**: A directory of images, organized into two folders: "cats" and "dogs."
- **Notebook/Script**: Contains code for data preprocessing, model training, evaluation, and hyperparameter tuning.

### Steps and Key Components

1. **Data Loading and Preparation**:
   - The images are loaded from Google Drive, resized to 15x15 pixels, and flattened into 1D arrays.
   - Each image is then labeled as "0" for cats and "1" for dogs.

2. **Data Preprocessing**:
   - Images are standardized using `StandardScaler` to improve model performance.
   - Data is split into training and test sets with an 80-20 split.

3. **Model Building**:
   - **Logistic Regression**: A basic linear model for initial classification.
   - **Decision Tree**: A tree-based classifier for improved accuracy.
   - **Random Forest**: An ensemble method to further enhance accuracy.

4. **Hyperparameter Tuning**:
   - `GridSearchCV` is used to find the best parameters for the Random Forest model, optimizing for the number of trees, depth, and splitting criteria.

5. **Evaluation**:
   - Model accuracy is evaluated using `accuracy_score` for each classifier.
   - A summary of actual vs. predicted values is created for analysis.

### Results

- Accuracy and performance metrics for each classifier are displayed.
- Best hyperparameters for the Random Forest model are also provided.

### License

This project is licensed under the MIT License.
