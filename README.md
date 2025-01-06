##Restaurant Recommendation System Repository
This repository contains a collection of code files designed to build a Restaurant Recommendation System using various techniques, including Content-Based Filtering, Collaborative Filtering, and Hybrid Models. The system delivers personalized restaurant recommendations based on user preferences and historical data.

Repository Structure
Code Files
1_RecomSystem_knowledge_based.py
Implements the logic for knowledge-based recommendations.

2_RecomSystem_Content_User_Entry.py
Allows user inputs for content-based recommendation generation.

2_RecomSystem_Restaurant_Content.py
Executes content-based filtering using restaurant-specific features.

3_Matrix_Multiplication.ipynb
A Jupyter Notebook for performing matrix multiplication operations.

3_RecomSystem_Matrix_Multiplication.py
Python script for implementing matrix multiplication.

4_Hybrid_Recommendation_model.ipynb
Notebook for developing a hybrid recommendation model.

4_RecomSystem_Hybrid.py
Python script that integrates hybrid recommendation logic.

5_Collaborative_Filtering.ipynb
Notebook showcasing the collaborative filtering model.

5_RecomSystem_Collaborative.py
Script implementing collaborative filtering logic.

Data Files
BangaloreZomatoData.csv: Raw data on restaurants in Bangalore.
BangaloreZomatoData_with_rest_id.csv: Processed data with restaurant IDs included.
UserOrdersData.csv: Dataset containing user orders and ratings.
USER AND RESTAURANT.xlsx: Additional data capturing user-restaurant interactions.
README.md: This file.
Features
1. Knowledge-Based Filtering
A decision support system that uses explicit knowledge about users, items, and recommendations to help users find relevant restaurants.

2. Content-Based Filtering
Recommends restaurants based on their features, such as cuisines and specialties.

3. Collaborative Filtering
Utilizes user-item interactions to provide recommendations based on user ratings and shared preferences.

4. Hybrid Model
Combines content-based and collaborative filtering techniques to enhance recommendation accuracy.

5. Matrix Multiplication-Based Recommendations
Employs matrix multiplication to match user preferences with suitable restaurant options.

Technologies Used
Python: Core programming language for the implementation.
Pandas: Data manipulation and preprocessing.
Scikit-learn: Machine learning tools, including cosine similarity and SVD.
Surprise: Collaborative filtering library leveraging the SVD algorithm.
Tkinter: For creating a graphical user interface (GUI).
Jupyter Notebooks: Used for development and model testing.
Installation
Step 1: Clone the Repository
bash
Copy code
git clone https://github.com/prateekmaj21/Restaurant-Recommendation-System.git
Step 2: Install Required Libraries
bash
Copy code
pip install -r requirements.txt
Step 3: Run the Application
Launch the Tkinter-based GUI app to interact with the recommendation system.

Future Improvements
Integration of additional recommendation algorithms.
Enhanced user interaction features.
Expansion of the dataset to include more restaurants and user interactions.
