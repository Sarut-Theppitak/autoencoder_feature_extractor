# autoencoder_feature_extractor
compare the result between using autoencoder as feature extractor(use only the bottle neck of the autoencoder) vs normal CNN

This project is in in form of Jupyter notebook. We use CIfar-10 dataset unthe the condition that you can use 50% of the following classes for training (bird, deer and truck).
We will train autoencoder firslt and feed the features to clasificaition to train the model separately.

What is included in this homework

1. How to deal with unbalanced data set
2. How to use balanced data generator for unbalanced dataset
3. How to apply data augmentation (standard + your own function) to your data generator (class Imagedatagen)
4. Visualize your images
5. How to create the model using custom Model class (inheritence)
6. Create your own loss fuction for autoencoder
7. Create call back function for learning rate step decay
8. How to use our trained autoencder as features extractor for clasification model training (autoencode + image generator)
9. How to visualize accuracy graph.

