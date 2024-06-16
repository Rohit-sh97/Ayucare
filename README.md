Ayucare is a web application designed to help users identify potential diseases based on their symptoms and recommend appropriate Ayurvedic medicines. This system leverages machine learning models to provide personalized health recommendations.

Key Objectives: 1.Disease Detection: Our primary objective is to accurately detect diseases based on the symptoms provided by the user.

2.Medicine Recommendation: Another crucial objective is to recommend eff ective Ayurvedic medicines for the detected diseases, promoting natural and holistic healing.

Components of Ayucare: 1. User Interface: A user-friendly web application where users can log in, enter their symptoms, and view recommendations. 2. Machine Learning Models: Two Decision Tree Classifi er models: one for disease detection and another for medicine recommendation. 3. Databases: A comprehensive database containing symptoms, diseases, and Ayurvedic medicine information.

TECHNOLOGICAL BASE :

Flask : Flask is a lightweight web framework for Python, ideal for building web applications. It handles HTTP requests, URL routing, template rendering with Jinja2, and API integration, facilitating communication between the frontend and backend.

scikit-learn : scikit-learn is a powerful machine learning library used for training and predicting with the Decision Tree Classifier models. These models are crucial for disease detection based on symptoms and recommending Ayurvedic medicines based on diagnosed diseases.

pandas : pandas is used for data manipulation and analysis. It handles loading, cleaning, and preprocessing the datasets, making it easier to prepare data for the machine learning models.

numpy : numpy supports efficient numerical operations and data transformations. It is essential for performing fast computations on large datasets and converting data formats between pandas DataFrames and numpy arrays for use in scikit-learn.

Decision Tree Classifier : Two Decision Tree Classifier models are implemented: Disease Detection Model: Predicts the most likely disease based on user symptoms. Medicine Recommendation Model: Recommends Ayurvedic treatments based on the diagnosed disease.
