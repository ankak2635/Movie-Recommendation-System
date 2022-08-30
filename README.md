# Movie-Recommendation-System
A movie recommendation system - It takes one movie name as user input and recommends 10 movies which the user might like based on his/her input (In this notebook the user input is - Pulp Fiction). 

**Dataset** - The dataset used contains around 5000 movies along with details like cast, crew, genere, budget etc.

**Modules:**

difflib - to get the closest match of the user input (In case they make spelling mistakes)

Tfidfvectorizer - to convert the text data into machine understandable vectors (numbers)

cosine_similarity - to get similarity score of the movies

**Limitations**

As the dataset contains only 4803 movies, your favourite movie may not be on the list. Hence, can't recommend movies for you. Also, lack of data may lead to some irrelavant recommendation
