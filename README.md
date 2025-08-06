# gpu-enabled-ml
The repository includes the notebooks used for testing the behavior of ML models when GPUs are available.

For now, it contains:

- *1-simple-nn.ipynb*, which contains a simple script to run a simple neural network (**NN**) with a simple dataset on either CPU, one GPU, or multiple GPUs.
- *2-MobileNet-CNN*, which contains a script that uses a pre-trained model called MobileNet-V2 to train a Convolutional Neural Network (**CNN**) for brain tumor classification. To download the dataset, a *Kaggle API key* is required (follow the instructions provided in the file). The training is performed on one GPU, while the evaluation is done only on the CPU (this can be removed to test exclusively on the GPU).
