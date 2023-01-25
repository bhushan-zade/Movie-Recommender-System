# movie_recommendation_system

A recommender system, or a recommendation system, is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give 
to an item. They are primarily used in commercial applications. (source - Wikipedia)

Mainly three types of recommendation systems in machine learning based on filtering are used to suggest product and services to the consumers.

1. Content Filtering

2. Collaborative Filtering

3. Hybrid Filtering

1. Content Filtering:

   In this algorithm, we try finding items look alike. Once we have item look like matrix,

      we can easily recommend alike items to a customer, who has purchased any item from the store.

2. Collaborative Filtering:

      Here, we try to search for look alike customers and offer products based on what his/her lookalike has chosen.

      This algorithm is very effective but takes a lot of time and resources.

3. Hybrid Filtering (Content Filtering + Collaborative Filtering):

   Both Content Filtering & Collaborative Filtering is used for the purpose. you-tube uses this algorithm for their strong recommendation system.

For this project, Content based filtering model more specifically item-based filtering concept has been used. Concept of Clustering, a subset of unsupervised machine learning has been used to build this recommendation system. TfidfVectorizer(Term Frequency & Inverse Document Frequency) of sklearn library has been used to count the frequency of the genres types. Hyper parameter of TfidfVectorizer gives better result. The TfidfVectorizer will tokenize documents, learn the vocabulary and inverse document frequency weightings, and allow you to encode new documents. Alternately, if you already have a learned CountVectorizer, you can use it with a TfidfTransformer to just calculate the inverse document frequencies and start encoding documents. Now for the finding the similarity in genres sigmoid_kernel has been used. (cosine, linear can also be used).

Web Development & Deployment: Python, Streamlit framework has been used for web development and the site was hosted in Streamlit Cloud as well.

Visit The Web App :https://bhushan-zade-movie-recommender-system-app-ipxnrc.streamlit.app/

# Visit For Details:

Data Gathered From: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Data per-processing & Model Applied: https://www.kaggle.com/code/bhu1111/movies-recommendation-system

Model Python-APP(app.py) File: https://github.com/bhushan-zade/Movie-Recommender-System/blob/main/app.py
