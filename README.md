# Navigating the Repo

### Different notebooks
- base_models.ipynb is used for the base line models.
- gnn_dgl.ipynb is the GNN implemented with the DGL library.
- attempt-at-GNN.ipynb is the GNN implemented with the PyG library.
- data_exploration.ipynb is a notebook that was used to pursue some exploratory data analysis.

### Data
- In the data folder, the 3 different data sets used in the project can be found: Books.csv, Ratings.csv, Users.csv. The data set can be found on Kaggle, see below.

[Book Recommendation Dataset - Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?select=classicRec.png)

### Other Material in repo
- Presentation_Slides.pptx is the class presentation that was done on Friday 31st.

# Abstract
In this project, we aim to develop a book recommender system employing the graph neural network (GNN) architecture and compare it to two baseline models that are respectively based on the standard recommendation system methods: collaborative filtering and content-based. The GNN algorithm enables the integration of contextual information of users and/or items, and is thus, potentially able to capture more dynamic, complex relationships than traditional matrix-filling algorithms. We will use a dataset containing book ratings, with user and item metadata (ID, demographics, etc.) Through the project, we would like to explore whether this state-of-the-art model can outperform more conventional methods such as collaborative filtering.

# Research Question
- How can Graph Neural Networks (GNNs) enhance a recommendation system for books when compared to standard models used for collaborative filtering, and content-based filtering?

 
# Project Split:
* Preprocessing (Linka)
* DGL set up (Linka)
* Base Models - Content-Based, Collaborative Filtering - (Naglis)
* Improve Base Models metrics (Linka)
* GNN model architecture with DGL (Barto)
* Improve on Preprocessing and DGL (Barto)
* GNN model architecture with PyG (Jules)
* Evaluate the model performance and do the presentation (Jules, Barto, Naglis, Linka)

# Useful Links:
[DGL Library](https://docs.dgl.ai/)
[PyG Library](https://pytorch-geometric.readthedocs.io/en/latest/)
[GNN example repo](https://github.com/je-dbl/GNN-RecSys)

# Relevant Papers:
- [A survey of GNNs for recommender systems](https://arxiv.org/pdf/2109.12843.pdf)
- [Product recommendation system using GNN](https://ceur-ws.org/Vol-3426/paper15.pdf)
- [Graph based product recommendation](https://nhtsai.github.io/graph-rec/)
