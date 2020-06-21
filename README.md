# Sketch Image Clustering based on Semantic Similarity

 - Worked on Tu Berlin Sketch dataset consisting of 20,000 sketch images belonging to 250 categories
 
 - Implemented Transfer Learning using fastai with ResNet34 as base architecture to achieve an accuracy of 78.90% on test dataset of 4000 sketch images outperforming the human accuracy of 73.10%
 
 - Clustered images based on semantic similarities by first converting predictions to high dimensional
vectors using spacy’s english corpus and then using pairwise cosine similarity of the vectors

## Example Clusters: 

* **Cluster 1**

![cluster_1](https://github.com/harshaldesai01/Sketch-Image-Clustering/blob/master/examples/ex_cluster_1.png)

* **Cluster 2**

![cluster_2](https://github.com/harshaldesai01/Sketch-Image-Clustering/blob/master/examples/ex_cluster_2.png)

* **Cluster 3**

![cluster_3](https://github.com/harshaldesai01/Sketch-Image-Clustering/blob/master/examples/ex_cluster_3.png)


* **Cluster 4**

![cluster_4](https://github.com/harshaldesai01/Sketch-Image-Clustering/blob/master/examples/ex_cluster_4.png)
