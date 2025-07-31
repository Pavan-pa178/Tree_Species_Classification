# Tree_Species_Classification

This AI-powered app helps students and nature enthusiasts identify and explore tree species based on image, location, and tree attributes.

🧠 Features
🌲 Recommend Trees by Location
📍 Find Locations for a Tree
📷 Identify Tree from Image
📊 Dataset Description
🗂️ Tree Metadata
🖼️ Tree Image Dataset
Structure: Folder-based, each folder named after a tree species
Use: Used to train the CNN for species recognition
Preprocessing:
Images resized to 224x224
Normalized pixel values
Augmented with flips, zoom, and rotation
🧪 Algorithms Used
🔍 Recommender System
🧠 CNN Classifier
📊 Preprocessing & Encoding
✅ How to Run
Run 5M_trees.ipynb to train the recommender and save:

tree_data.pkl
scaler.joblib
nn_model.joblib
Run tree_CNN.ipynb to train the image classifier and save:

basic_cnn_tree_species.h5
