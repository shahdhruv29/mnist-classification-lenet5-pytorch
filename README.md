# mnist-classification-lenet5-pytorch
Trained MNIST dataset from scratch using Lenet-5 Architecture in Pytorch

Used the [MNIST](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv) dataset which consists of ten numbers, 0-9. 
Here the ten class classification is performed using the LeNet-5 architecture from the [paper](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf) titled "Gradient-based learning applied to document recognition" by Y.LeCun *et. al*.

In mlp_model2.ipynb classification is done on only two digits,i.e. 4 and 9 which are somewhat similar looking to the naked eye. Further in mlp_model3.ipynb three class classification is done between the digits 4, 9 and 3 and it is observed that the model confuses a bit between 4 and 9 in this case and accuracy reduces by nearly ~1%.
