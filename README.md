# Unsupervised Clustering Algorithm for Finding Compatible Roommates

## Project Overview
This project aims to create an unsupervised clustering algorithm to find compatible roommates based on specific criteria like lifestyle habits, hobbies, social preferences, and personal traits (e.g., age, income, and gender). The algorithm is designed as a foundational component of a future application called **Hommies**, which seeks to simplify the process of finding ideal roommates.

## Motivation
The idea originated from personal experiences and feedback from others regarding the challenges of finding suitable roommates when moving to a new city. The current random and uncertain process often leads to uncomfortable living situations, negatively affecting the quality of life at home. This project addresses the gap by offering a data-driven, scalable solution.

## Key Features
- **Data Collection**: Developed a custom dataset via a Google Forms questionnaire, collecting 226 responses from university students and young adults.
- **Data Preprocessing**:
  - Handled missing values using statistical imputation.
  - Processed outliers to normalize data distributions.
  - Encoded categorical variables using One-Hot Encoding and ordinal-to-numeric transformations.
- **Unsupervised Learning Models**:
  - Implemented clustering methods, including k-means, Gaussian Mixture Models (GMM), and DBSCAN.
  - Used PCA (Principal Component Analysis) to improve model performance by reducing dimensionality and increasing variance.
- **Evaluation Metrics**:
  - Assessed clustering effectiveness using the Silhouette Index, Elbow Method, and visualizations (2D scatter plots).
- **Scalable Infrastructure**:
  - Connected the dataset to SQLite for future integration with automated workflows in the application.

## Methodology
The project followed three main phases:
1. **Qualitative Analysis**:
   Conducted semi-structured interviews to identify variables critical for roommate compatibility.
2. **Exploratory Data Analysis**:
   Used Python and Google Forms to analyze data trends and validate survey structure.
3. **Clustering and Evaluation**:
   Applied unsupervised learning algorithms and iteratively refined data preprocessing steps to improve clustering results.

## Tools and Technologies
- **Programming**: Python (Google Colab)
- **Data Handling**: Pandas, NumPy, SQLite
- **Machine Learning**: scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Collaboration**: Google Forms, Canva

## Key Results
- Successfully implemented a clustering algorithm with acceptable performance metrics, achieving a **Silhouette Index of 0.5** in the best-case scenario after extensive data preprocessing.
- Identified the optimal number of clusters as 5 based on the Elbow Method and scatter plot analysis.
- Integrated PCA to explain over 70% of data variance, enabling better cluster differentiation.

## How to Use
Clone the repository:
   ```bash
   git clone https://github.com/diegico/Clustering-algorithm-to-find-roommates
   # Open the following link in your browser:
  https://colab.research.google.com/drive/1Jd8S8nonUhCYVRk9LpYoNXoiC009gUqZ?usp=sharing
  Install the necessary Python libraries (if running locally):
  pip install pandas numpy matplotlib scikit-learn



