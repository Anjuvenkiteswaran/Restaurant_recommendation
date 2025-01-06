# Restaurant Recommendation System

This repository contains the code and resources for building a **Restaurant Recommendation System** using multiple techniques, including **Content-Based Filtering**, **Collaborative Filtering**, and **Hybrid Models**. The system delivers personalized restaurant recommendations based on user preferences and historical data.

---

## Repository Structure

### **Code Files**
- **`1_RecomSystem_knowledge_based.py`**: Implements the logic for knowledge-based recommendations.
- **`2_RecomSystem_Content_User_Entry.py`**: Accepts user inputs for content-based recommendations.
- **`2_RecomSystem_Restaurant_Content.py`**: Executes content-based filtering using restaurant features.
- **`3_Matrix_Multiplication.ipynb`**: Jupyter Notebook for matrix multiplication operations.
- **`3_RecomSystem_Matrix_Multiplication.py`**: Python script for matrix multiplication.
- **`4_Hybrid_Recommendation_model.ipynb`**: Notebook for developing a hybrid recommendation model.
- **`4_RecomSystem_Hybrid.py`**: Python script implementing hybrid recommendation logic.
- **`5_Collaborative_Filtering.ipynb`**: Notebook for collaborative filtering model development.
- **`5_RecomSystem_Collaborative.py`**: Script implementing collaborative filtering logic.

### **Data Files**
- **`BangaloreZomatoData.csv`**: Raw data of restaurants in Bangalore.
- **`BangaloreZomatoData_with_rest_id.csv`**: Processed data including restaurant IDs.
- **`UserOrdersData.csv`**: Dataset containing user orders and ratings.
- **`USER AND RESTAURANT.xlsx`**: Additional user-restaurant interaction data.
- **`README.md`**: Project overview and setup instructions.

---

## Features
- **Knowledge-Based Filtering**: Provides recommendations using explicit knowledge about users, restaurants, and preferences.
- **Content-Based Filtering**: Suggests restaurants based on their features, such as cuisines and specialties.
- **Collaborative Filtering**: Leverages user-item interactions to recommend restaurants based on similar user preferences.
- **Hybrid Model**: Combines content-based and collaborative filtering for enhanced accuracy.
- **Matrix Multiplication-Based Recommendations**: Matches user preferences with restaurants using matrix multiplication techniques.

---

## Technologies Used
- **Python**: Core programming language for implementation.
- **Pandas**: Data manipulation and processing.
- **Scikit-learn**: For machine learning tasks like cosine similarity and SVD.
- **Surprise**: Library for collaborative filtering using the SVD algorithm.
- **Tkinter**: GUI development library for user interaction.
- **Jupyter Notebooks**: Used for exploratory development and model building.

---

## Installation

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/prateekmaj21/Restaurant-Recommendation-System.git
