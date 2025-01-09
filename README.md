# GAN Self-Learning Project
[![Python](https://img.shields.io/badge/Python-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
![Generative Adversarial Networks](https://img.shields.io/badge/GAN-Generative%20Adversarial%20Networks-blueviolet.svg)
![MNIST Dataset](https://img.shields.io/badge/Dataset-MNIST-blue.svg)
![Last Updated: August 2022](https://img.shields.io/badge/Last%20Updated-August%202022-green.svg)

## Backup of GAN Learning Project (August 2022)

> [!NOTE]
> The project explores various GAN architectures and improvements through iterative versions.

> [!IMPORTANT]
> This project is a personal learning exercise in understanding and implementing different GAN techniques.

## References

- The YouTube video series "Generative Adversarial Networks (GANs)", Aladdin Persson, at https://www.youtube.com/playlist?list=PLhhyoLH6IjfwIp8bZnzX8QR30TRcHO8Va

## Setups
**Environment**:
- Python version: 3.x
- Framework: PyTorch
- Dataset: MNIST
- Runned on Google Colab

## Experiments
### MNIST Digit Generation
Explored various GAN architectures:
- Standard GAN
- Wasserstein GAN (WGAN)
- Conditional WGAN

### Key Experiments
- Experimented with different learning rates
- Observed the phoenomenon of mode collapse and the sensitivity of the GAN architecture to the learning rate
- Understanding the architecture of GAN, improvements made by WGAN, and also the principles of providing class conditions to GANs

### Experiment Results
1. Vanilla GAN 
   [![Version v2](https://img.shields.io/badge/Version-v2-blue.svg)](202208011748_GAN_mnist_v2%20good/202208011748_GAN_mnist_v2_final.ipynb)
   [![Version v3](https://img.shields.io/badge/Version-v3-blue.svg)](202208021155_GAN_mnist_v3%20good%2Cinterupted/202208021155_GAN_mnist_v3.ipynb)
   [![Version v4](https://img.shields.io/badge/Version-v4-blue.svg)](202208041411_GAN_mnist_v4%20faster%20GAN/202208031401_GAN_mnist_v4_epoch100_ed.ipynb)
   <table style="text-align:center">
      <tr>
         <th>v2 (100 epochs)</th>
         <th>v3 (35 epochs *early stopped)</th>
         <th>v4 (100 epochs)</th>
      </tr>
      <tr>
         <td><img src="202208011748_GAN_mnist_v2%20good/202208011748_step50_ganoutput.png" width="200" height="200" /></td>
         <td><img src="202208021155_GAN_mnist_v3%20good,interupted/202208021155_step35_ganoutput.png" width="200" height="200" /></td>
         <td><img src="202208041411_GAN_mnist_v4%20faster%20GAN/ezgif-4-2d7be035dd.gif" width="200" height="200" /></td>
      </tr>
   </table>

2. Wasserstein GAN (WGAN) 
   [![Version v5](https://img.shields.io/badge/Version-v5-blue.svg)](202208051901_GAN_mnist_v5_WGAN/202208051901_GAN_mnist_v5_WGAN%20epoch100.ipynb)
   <table style="text-align:center">
      <tr>
         <th>v5 (100 epochs)</th>
      </tr>
      <tr>
         <td><img src="202208051901_GAN_mnist_v5_WGAN/ezgif-4-98172f4be1.gif" width="200" height="200" /></td>
      </tr>
   </table>

3. Conditional Wasserstein GAN (incomplete)
   [![Version v6](https://img.shields.io/badge/Version-v6-blue.svg)](202208061306_GAN_mnist_v6_conditional%20WGAN/202208061306_GAN_mnist_v6_Conditional_WGAN.ipynb)