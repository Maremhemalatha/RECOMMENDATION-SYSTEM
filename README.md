# RECOMMENDATION-SYSTEM

COMPANY:CODTECH IT SOLUTIONS

NAME:Marem Hemalatha

INTERN ID:CT04DG1515

DOMAIN:Machine Learning

DURATION:4 WEEKS

MENTOER:NEELA SANTOSH

DESCRIPTION:

*TASK 4:RECOMMENDATION SYSTEM*

The objective of Task 4 is to build a Recommendation System using Collaborative Filtering or Matrix Factorization techniques. A recommendation system is an intelligent software component that predicts users’ preferences and suggests products or content that the user might like. In this task, we use the MovieLens 100K dataset to develop a personalized movie recommendation system based on user ratings.
The MovieLens 100K dataset is one of the most commonly used benchmark datasets in recommendation system research. It consists of 100,000 ratings (from 1 to 5) given by 943 users on 1,682 movies. Each user has rated at least 20 movies. The dataset is widely used for experimenting with collaborative filtering algorithms due to its clean and structured nature.

*TOOLS AND TECHNOLOGIES USED*:

For this task, I used several tools and Python libraries to build and evaluate the recommendation model:

•	Programming Language: Python

•	Editor Platform: Jupyter Notebook (launched using Command Prompt)

•	Libraries Used:

o	surprise: A Python scikit for building and analyzing recommender systems.
o	pandas: For managing and analyzing tabular data.
o	matplotlib: For visualizing the predictions using charts and plots.
o	numpy: For efficient numerical computations.
The main machine learning algorithm used for this task is Singular Value Decomposition (SVD), a Matrix Factorization technique provided by the surprise library. It is effective in capturing latent factors between users and items, thereby producing highly accurate predictions.

*TASK EXECUTION AND PROCESS*:

We followed a systematic process to complete the task:

1.	Dataset Loading:
We used the built-in MovieLens 100K dataset available through the surprise library. The dataset was loaded and split into a training set (80%) and a test set (20%) for evaluation purposes.
2. Model Selection and Training
We used the SVD (Singular Value Decomposition) algorithm from surprise. It’s a matrix factorization technique that decomposes the user-item interaction matrix into lower-dimensional latent factors, which helps predict unknown ratings.
The SVD model was trained on the training set using the .fit() method.
3. Model Evaluation
Once the model was trained, we used it to predict ratings for the test set. The accuracy of the model was evaluated using two standard metrics:
•	RMSE (Root Mean Squared Error): Measures the square root of the average squared differences between actual and predicted ratings.
•	MAE (Mean Absolute Error): Measures the average of the absolute differences between actual and predicted ratings.
Both metrics help in assessing how well the model is performing in terms of prediction accuracy.
4. Generating Recommendations
A function was created to recommend the Top-N movies for any given user. This function:
•	Converts user IDs to inner IDs used by the trained model.
•	Identifies items not yet rated by the user.
•	Predicts ratings for all unrated items.
•	Sorts the items by predicted rating in descending order.
•	Returns the top-N items as recommendations.
We tested this recommendation function on User ID 196, and printed the top 5 movie suggestions based on predicted ratings.
5.Visualization
To improve the interpretability of the output, we plotted a histogram showing the distribution of predicted ratings. This helps in understanding how the model's predicted scores are spread across the rating scale.

*PLATFORM USED*:

All the coding and model training were performed using Jupyter Notebook, which was launched through the Command Prompt inside a dedicated Python virtual environment named codtech_env. Jupyter Notebook offers an interactive and user-friendly interface for testing and displaying code output, graphs, and markdown documentation.
This environment was ideal for:
•	Writing modular code in cells
•	Visualizing charts and evaluation metrics
•	Running experiments and recording outputs in a single file

*REAL-WORLD APPLICATIONS*:

Recommendation systems are widely used across various industries:
•	E-commerce platforms like Amazon, Flipkart, and Meesho use them to suggest products.
•	Streaming services like Netflix, YouTube, and Spotify use them to recommend movies, shows, and songs.
•	Social media platforms like Facebook and Instagram use them to suggest friends, posts, and ads.
•	Educational platforms like Coursera and Udemy use them to recommend courses.
In this task, we simulated how such systems can be built using public datasets and open-source tools to deliver personalized experiences.

*CONCLUSION*:

To summarize, this task helped us build a functional recommendation engine using collaborative filtering with matrix factorization techniques. We learned how to load and process datasets, build recommendation models using surprise, evaluate their accuracy, and generate personalized suggestions. The task reinforced important concepts in machine learning, especially those related to personalization and user-item interactions, which are crucial in modern data-driven applications.

*OUTPUT*:

<img width="1920" height="979" alt="Image" src="https://github.com/user-attachments/assets/f501f081-4e9c-4b67-93b2-ca4e9f1f5d9d" />
