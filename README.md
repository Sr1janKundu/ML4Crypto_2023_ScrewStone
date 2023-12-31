# Data Science Challenge @ Interdisciplinary Workshop on Machine Learning for Cryptology (ML4Crypto 2023)

This Data Science Challenge is a part of the second version of interdisciplinary workshop on "Machine Learning for Cryptology" (ML4Crypto 2023) to be held during November 8-10, 2023 at Indian Statistical Institute, Kolkata. The webpage for the workshop is: https://www.isical.ac.in/~caiml/ml4crypto2023

The said Data Science Challenge is about performing differential cryptanalysis on some popular ciphers with machine learning. The attack is posed as a two-class classification (supervised learning) problem. The participants are welcome to employ any sort of classification approach, be it classical machine learning, deep learning, or others.

A large set of plaintexts is generated in the form of bitstreams. These plaintexts are converted into ciphertexts in the form of bitstreams. There are three columns in the dataset. The first column denotes the ID of the ciphertext. The second column comprises either the ciphertexts in the form of bitstreams generated by applying one particular cipher or random bitstreams. Each bitstream (ciphertexts / random) has a length of 64 bits. The third column consists of the labels (0 and 1), which denote the bitstream type.

The dataset is segregated into two parts - training and test. The training dataset comprises 250,000 bitstreams. The training dataset includes the labels. The test dataset comprises 62,500 bitstreams without any labels. The labels of the test dataset are to be predicted. The submitted trained models will be applied on the test dataset by the organizers.

The performance metric for the two-class classification on the test dataset will be the accuracy score.

NOTE: This classification task is challenging and anything beyond 50% may be a non-trivial result. So, you are encouraged to make the final submission even if your classification accuracy is poor.
