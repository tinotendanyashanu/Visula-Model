# Visula-Model


This code demonstrates how to train a Decision Tree Classifier model on a music dataset and visualize the decision tree using Graphviz.

## Libraries
The following libraries are imported:

pandas: Used to read and manipulate the dataset
DecisionTreeClassifier from sklearn.tree: Used to create the decision tree model
tree from sklearn: Used to export the decision tree model in Graphviz format
## Data
The music data is imported from a CSV file using the pd.read_csv function.

## Inputs and Outputs
The input features are all columns in the dataset except for the 'genre' column, which is the output target.

## Model
The model is created using the DecisionTreeClassifier function from sklearn.tree and trained on the entire dataset using the fit method.

## Visualization
The decision tree model is exported in Graphviz format using the export_graphviz function from sklearn.tree. The resulting file is saved as music.dot. The feature_names argument specifies the names of the input features, and the class_names argument specifies the names of the output classes. The label, rounded, and filled arguments are optional and control the appearance of the resulting graph.


<img width="586" alt="image" src="https://user-images.githubusercontent.com/49924409/229378265-9911c319-dedf-4c02-bbe2-ec637aa9e41b.png">
