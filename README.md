## Abstract

<p align="justify">
Adversarial attacks play a key role in making robust neural networks for various computer vision tasks. To make a proper mechanism for defending against adversarial attacks, understanding the neural network’s behaviour is very important. Recent studies show that manifold analysis has been capable of understanding the neural network performance by evaluating linear separability among the classes by analysing the number of activations of each layer of a convolutional neural network (CNN) architecture. The purpose of this study is to evaluate the linear separability of manifolds while we are changing the input space by applying a few adversarial perturbations to the images. Therefore, the perturbed images were created by using Gaussian noise levels as adversarial attacks. The baseline analysis was done for the ResNet18 pre-trained model with the CIFAR10 dataset and obtained mean-field theoretic manifold analysis (MFTMA) measurements for the evaluations. The analysis results show that the increase in Gaussian noise level impacts the linear separability of the object manifolds. reducing manifold capacity and increase of the manifold dimension will lead to making model predictions as misclassification. As a future research direction, this approach can be extended to create a white-box adversarial attack framework by leveraging MFTMA analysis to make guided perturbations and improve the robustness of the deep neural network models.

### Code Implementation
  <ul>
    <li><a href="https://github.com/pushpikaprasad/MFTMA_with_Gaussian_Noise/blob/master/ResNet18_Model_Preparation_with_CIFAR10_dataset.ipynb">ResNet18_Model_Preparation_with_CIFAR10_dataset.ipynb</a></li>
    <li><a href="https://github.com/pushpikaprasad/MFTMA_with_Gaussian_Noise/blob/master/Manifold_data_preparation.ipynb">Manifold_data_preparation.ipynb</a></li>
    <li><a href="https://github.com/pushpikaprasad/MFTMA_with_Gaussian_Noise/blob/master/MFTMA_with_Gaussian_Noise.ipynb">MFTMA_with_Gaussian_Noise.ipynb</a></li>
  </ul>

<br> <a href="https://github.com/pushpikaprasad/MFTMA_with_Gaussian_Noise/blob/master/Preliminary%20research%20work.pdf">Preliminary Research work</a>
</p>


