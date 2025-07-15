# Brain Tumor Image Clustering Using ResNet50 and  KMeans
This project applies deep feature extraction using a pre-trained ResNet50 model followed by unsupervised clustering with KMeans to identify and group brain tumor images into clusters. The approach also visualizes feature space using PCA and evaluates clustering quality using the Silhouette Score.

# Features
  Loads and preprocesses brain tumor images from Google Drive

  Uses ResNet50 (without top layer) to extract high-dimensional features

  Clusters images into 4 groups using KMeans

  Reduces feature space to 2D using PCA for visualization

  Displays cluster-wise sample images

  Saves cluster assignments to a .csv file

  Evaluates clustering quality with the Silhouette Score
