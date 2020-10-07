# OCP6
## Project 6 OPENCLASSROOMS - Automatically classify consumer goods
For this project we have a dataset of 1050 products with their photo and description.  
Each product is affected to one category ('Watches', 'Computers', 'Baby Care', etc.)

The purpose of the project is to evaluate the possibility to automatically classify these products according to their photo or description, or a combination of both.

## Notebook N° 1
Exploration of the dataset.  
Visualization of some images for each category of products

## Notebook N° 2
Focus on the images :
- Image preprocessing (Resizing, adjusting colors and contrast)
- Feature extraction with ORB, creation of 'Bags of words' with K-Means
- Supervised Classification (Random Forest, Support Vector Machine)
- Implementation of a CNN
- Transfer Learning on ImageNet
- Feature Extraction with a pre-trained CNN
- Unsupervised Classification (K-Means, Gaussian Mixture, DB Scan)
- Dimensional Reduction (PCA)
- Interactive Visualisation of the clusters (t-SNE Projection) with Plotly

## Notebook N° 3
Focus on the descriptions (text data) :
- Natural Language Processing (Cleaning, Tokenization, Lemmatization of the text)
- Count Vectorizer, relative term frequency (tf-idf)
- Unsupervised Approches to find topics : LDA, NMF
- Clustering of text features (K-Means, Gaussian Mixture, DB Scan)
- Interactive Visualisation of the clusters (t-SNE Projection) with Plotly

Combination of the text and image features :
- Supervised and unsupervised learning
- Feature importance
- Conclusion
