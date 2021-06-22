# DWCNN_TL
We introduce a parameter-based approach of cross-subject transfer learning for improving the poor-performing individuals in MI-based BCI systems, 
pooling data from labeled EEG measurements and psychological questionnaires via kernel embedding. To this end, a Deep\&amp;Wide neural network for 
MI classification is implemented to pre-train the network from the source domain. Then, the layer parameter layers are transferred to initialize the 
target network within a fine-tuning procedure to recompute the Multilayer Perceptron-based accuracy. To perform data fusion combining categorical with 
the real-valued features, we implement the stepwise kernel matching via Gaussian embedding.
