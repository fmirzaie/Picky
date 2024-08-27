# Picky: LLM/RAG-based Movie Recommendation System 
## Overview

Picky project is a movie recommendation system that involves three distinct recommendation techniques to provide a holistic and personalized user experience.

Recommender systems are algorithms designed to suggest products, content, or services to users based on their preferences and behaviors. They analyze data such as past interactions, ratings, and user profiles to predict what users might like. Common techniques include collaborative filtering, which leverages similarities between users or items, and content-based filtering, which recommends items similar to those a user has liked based on item features. Recommender systems are widely used in various domains, including e-commerce, streaming services, and social media, to enhance user experience and engagement. 

In this project, we will explore various approaches to build a movie recommendation system:

1. **Collaborative Filtering**: This approach recommends movies based on user interactions and preferences. By analyzing patterns and similarities between users, Picky identifies movies enjoyed by others with similar tastes, making personalized suggestions based on collective user behavior.

2. **Content-Based Recommendation**: Picky also provides content-based recommendations, which focuses on the attributes of movies. It analyzes features such as genre and tags to suggest movies that align with the user's specific interests and preferences.

3. **RAG (Retrieval-Augmented Generation)**: Combining document retrieval from a vectorstore and large language models, RAG enhances Picky’s recommendations by fetching relevant information from a database and generating context-aware suggestions. This allows the system to provide recommendations that are both contextually relevant and tailored to user queries.