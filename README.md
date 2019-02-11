# fashion-mnist

Good explanations

umap-learn provides the UMAP manifold based dimension reduction algorithm. The package provides an sklearn compatible interface to t-SNE like dimension reduction technique that has better runtime performacne than t-SNE and often preserves more global structure than t-SNE.

1. The file UmapFMNIST uses fashion-mnist dataset and explores different visualisation on the data set. The data is fit and visualized in 2-D using the seaborn pair plots.

After than to make visulaization more interesting the 3-D visulaization of the data is done using plotly. Plotly not only gives a 3-d Visulaization but also a very intreactive visulaiztion with features like zoom-in, zoom-out, etc to further visualize the 3-D data in a better way.

The label have been defined with the graph with each coluor represnting a different type.

Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.

2. The second file explores more on the training and testing datasets of fashion-MNIST. SKlearn is used to split the data into test and train sets after which the keras and tesorflow is used to predict the test data, the predictions are visualised with the correct results and predicted results. The confusion matrix is plotted after the predictions and is visulaised using the heatmap. After which precision, recall and f1-score are printed. 

Confusion matrix - A confusion matrix is a table that is often used to describe the performance of a classification model (or "classifier") on a set of test data for which the true values are known.
Heatmap - They are good visuilaizers for matrix data as they represent the relation, it can be color cordinated into coolwarm and other types for a better visulaization and density. Also values can be plotted in terms of similairty on heatmap.

In pattern recognition, information retrieval and binary classification, precision (also called positive predictive value) is the fraction of relevant instances among the retrieved instances, while recall (also known as sensitivity) is the fraction of relevant instances that have been retrieved over the total amount of relevant instances. Both precision and recall are therefore based on an understanding and measure of relevance.

Modular and Idiomatic code

Two files were used to show two different appraches which were adopted on the dataset, one was more towards intrecative display and other was into training the model comparing the results.
Modular code approach has been used which can be reused for different datasets intreactive plotting and training and testing.

Clear goals
I wanted to play with the visulaization of the dataset, as it a 3-D dataset itself and exlporing plotly was a good experince. I also found that the training and testing of fashion-MNIST doesnt give great accuracy,I wanted to exlpore this part and train, test and predict the values of the dataset. Also for analysing the prediction results I explore machine learning evalutaion metrices like confussion matrix, precision, recall.

Tying-back final output to original goals
The predictions of the fashion-MNIST can further be improved if try to use RNN over the datasets, which would make more calucluations on the points and lines of the image and clearly identify it using the Keras and tensorflow network.

Different viewpoints
Visulaization can be further improved, I can keep my future work as to explore and magnify different parts of the plotly in 3-D intreactive way.

Visual explanations
Different visual explations have been used like 2-D plots, 3-D plots, heatmaps, grid plotting, seaborn, plotly, matplotply have been used pair plotting have been used.

Awareness of knowledge boundaries ("What do I know about how much I know!").
I am aware about the different data analysis, visualilzation, test and train and prediction evaluation. I also exlpore tensorflow and keras and I would like to deep dive further into deep learning and exploring more into the improvement of the predictions.
