# Music Recommendation System for Spotify
A content-based music recommendation system built using K-Nearest Neighbors and cosine similarity, trained on Spotify's audio features across 125 genres, with an autonomous autoplay queue engine — built and evaluated on Kaggle.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Models Used](#models-used)
- [Results](#results)


---

# Overview
Music recommendation — suggesting the right song at the right moment — is one of the core problems in audio streaming platforms. This project builds a content-based filtering system that recommends songs by measuring audio similarity between tracks using Spotify's audio analysis features.Unlike collaborative filtering (which needs user history), this system works purely from the song's sonic characteristics — making it effective even for new users or obscure tracks with no listening history.The pipeline covers data cleaning, feature engineering, normalization, KNN model training, three recommendation modes, an autonomous autoplay queue, and evaluation via genre hit rate — all structured to run end-to-end in Kaggle.

# Dataset
**Source:** [Spotify Tracks Dataset — Kaggle](https://www.kaggle.com/datasets/yashdev01/spotify-tracks-dataset/data)

The dataset contains information about Spotify tracks across 125 different music genres. Each row represents a single song and each column represents a specific attribute related to that track. Along with basic metadata such as track name, artist, and genre label, the dataset includes several numerical audio features extracted by Spotify's audio analysis system. These features quantitatively describe the musical characteristics and mood of each track, making it highly suitable for recommendation, genre classification, clustering, and mood prediction tasks.

### Dataset Features
<img width="674" height="883" alt="image" src="https://github.com/user-attachments/assets/576012e5-66aa-46b7-99dc-7ba430d0ef91" />
<img width="1638" height="736" alt="image" src="https://github.com/user-attachments/assets/9aecf29f-7edf-426c-b2d7-163517ed4244" />
<img width="1631" height="868" alt="image" src="https://github.com/user-attachments/assets/0567fe80-cb71-48cd-8f32-5291138e685a" />
<img width="1636" height="877" alt="image" src="https://github.com/user-attachments/assets/3714ae4b-c6b6-4004-88ae-f96e51f79187" />
<img width="1625" height="878" alt="image" src="https://github.com/user-attachments/assets/bff3b7b6-6ee1-40ff-a588-f7ddcfb3ede4" />
<img width="1625" height="369" alt="image" src="https://github.com/user-attachments/assets/88a5a454-86ce-4977-b2f0-ac2e960924f6" />





## Project Workflow
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/1581f660-5699-4fe0-86e4-a36bf7bfb2a9" />


## Models Used

### K-Nearest Neighbours 
K‑Nearest Neighbor (KNN) is a simple and widely used machine learning technique for classification and regression tasks. It works by identifying the K closest data points to a given input and making predictions based on the majority class or average value of those neighbors. KNN is also called as a lazy learner algorithm because it does not learn from the training set immediately instead it stores the entire dataset and performs computations only at the time of classification. In the KNN algorithm k is just a number that tells the algorithm how many nearby points or neighbors to look at when it makes a decision.

## Results:

### Features added
<img width="561" height="379" alt="image" src="https://github.com/user-attachments/assets/aab05498-40b0-4465-9fbc-f614d0ee72a3" />

### Features Considered
<img width="689" height="109" alt="image" src="https://github.com/user-attachments/assets/7ab6d9f5-8e57-4f96-bc45-85490d40eade" />


### Feature Distribution
<img width="1989" height="1377" alt="image" src="https://github.com/user-attachments/assets/630fc779-ac8f-4c6f-8b22-921f586df672" />


### Feature Correlation Matrix
<img width="1301" height="1090" alt="image" src="https://github.com/user-attachments/assets/6021d01a-b026-41f8-9c2c-2c97d65d6ac0" />


### Genre Hit Rate vs Top-K
<img width="786" height="390" alt="image" src="https://github.com/user-attachments/assets/578e8b26-fed2-444e-8d7c-7b223618581a" />
<img width="348" height="40" alt="image" src="https://github.com/user-attachments/assets/0bd4a161-110b-402d-8864-cd0524e2872e" />


### Feature Importance
<img width="889" height="590" alt="image" src="https://github.com/user-attachments/assets/1dc57065-75d6-4987-9c13-77c4348719ee" />
<img width="249" height="161" alt="image" src="https://github.com/user-attachments/assets/303d7405-d3c2-4d49-9194-50007833d10e" />




### Mood Score and Speechiness/Instrumentalness/Vocal Presence
<img width="1590" height="495" alt="image" src="https://github.com/user-attachments/assets/09ac667a-2d25-4e1d-8e08-c5c489ba0d1e" />



### Demo of song recommender and auto-queue function
<img width="801" height="556" alt="image" src="https://github.com/user-attachments/assets/7f7277b1-9085-42bf-836e-1ab9351fcb7d" />
<img width="588" height="350" alt="image" src="https://github.com/user-attachments/assets/1a14df59-95e5-45b6-b59a-11537ed874c1" />


















