# D2NN-with-Pytorch

## Environment:

torch==1.12.1
torchvision==0.13.1
numpy==1.23.5
matplotlib==3.7.1
tqdm==4.65.0

------------------------------------------------

Reading Sequence

D2NN $\Rightarrow$ Beam-Diffraction $\Rightarrow$ D2NN-plus

D2NN-plus = D2NN + Beam-Diffraction

### D2NN

1. Only ***5 Phase Layers*** are concerned.
2. The ***Beam Propagation Evolution*** are not concerned.
3. The rate of training is ***Faster***.
4. The Accuracy is limited to ***70-80%*** for 5 diffractive layers.

### D2NN-plus

1. The free space is ***Totally Meshed***.
2. The ***Beam Propagation Evolution*** are concerned.
3. Only 5 meshed layers are attached with ***Phase Learning***.
4. ***Similar Accuracy*** with D2NN.

The accuracy of D2NN model is troubling me for a long time. It seems difficult to be optimized to 90% accuracy.



---------------

**Congratulations!**

By using 4F system D2NN, I've got **97%** Accuracy for **MNIST** validation dataset.

Now, I'm trying to apply D2NN on **CIFAR-10** dataset with multichannel explorations. ***God Blessing Me !***
