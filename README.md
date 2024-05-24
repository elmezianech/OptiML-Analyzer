# OptiML-Analyzer
OptiML-Analyzer is designed to provide users, with hands-on experience in programming and machine learning. The application, built with Streamlit, facilitates the entire machine learning pipeline from importing or creating data to exporting trained models. Users can leverage multiple machine learning algorithms for data analysis, ensuring robust and reliable results with advanced visualization tools.

## Key Features
### 1. Intuitive User Interface
OptiML-Analyzer features an intuitive interface built with Streamlit, organized into several tabs for easy navigation:

#### Home Page
- **Purpose**: Provides a welcoming interface for exploring and analyzing data.
- **Features**: Introduction to the platform with user-friendly navigation.

#### Data Creation and Import
- **Purpose**: Allows users to generate new datasets or import existing ones from various sources.
- **Features**: 
  - Data creation interface
  - Data import interface
  - Problem type selection (classification, regression, or clustering)

### 2. Data Representation
- **Purpose**: Provides advanced graphical visualization of data.
- **Features**: 
  - Column selection for customized visualization
  - Integrated graph types: Scatter Plot, Line Plot, Bar Plot, Box Plot, Heatmap

### 3. Data Cleaning
- **Purpose**: Facilitates essential data preprocessing operations.
- **Features**: 
  - Column selection for deletion
  - Duplicate row removal
  - Missing value replacement (options: 0, Mean, Median, Mode)
  - Conversion of object columns to float
  - Categorical variable encoding (One-Hot, Ordinal, Label)
  - Numeric variable normalization

### 4. Data Preparation
- **Purpose**: Prepares data for analysis by handling different problem types and splitting datasets.
- **Features**: 
  - Conditional display of target variable section
  - Training-test split customization (random_state, train-test ratio)

### 5. Data Transformation
- **Purpose**: Applies specific transformation techniques based on user needs.
- **Features**: 
  - Principal Component Analysis (PCA) with elbow method visualization
  - Synthetic Minority Over-sampling Technique (SMOTE) for imbalanced datasets

### 6. Machine Learning Algorithm Selection and Model Training
- **Purpose**: Provides flexibility in choosing and customizing machine learning algorithms.
- **Features**: 
  - Algorithm selection based on problem type
  - Adjustable hyperparameters for each algorithm

### 7. Model Evaluation
- **Purpose**: Summarizes model evaluation with detailed metrics.
- **Features**: 
  - Classification: Classification report, Confusion matrix, ROC curve, Precision-Recall curve
  - Regression: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R2), Residuals plot
  - Clustering: Silhouette score, Inertia, Cluster visualization

### 8. Model Export
- **Purpose**: Allows saving the trained model for future use.
- **Features**: 
  - Export using joblib
  - Customizable file name and storage location

