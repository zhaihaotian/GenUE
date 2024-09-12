# GenUE
GenUE-LNL: Generative Model for Uncertainty Estimation in Label-Noise Learning

## Abstract
In Label-Noise Learning (LNL), traditional methods such as DivideMix often rely on Gaussian Mixture Models (GMM) to separate noisy and clean samples based on loss values. However, these methods struggle with complex noise distributions. To address this, we propose GenUE-LNL, a framework that uses a generative model for uncertainty estimation. GenUE-LNL integrates a diffusion model as the classifier head, generating multiple samples and leveraging statistical distributions like chi-square or t-distribution to better estimate uncertainty. This enhanced uncertainty estimation allows for more robust handling of noisy samples, improving classification performance in noisy environments.
Our extensive experiments on benchmark datasets, including CIFAR-10, CIFAR-100, ImageNet-1K, Clothing1M, and Food101, demonstrate that GenUE-LNL significantly outperforms traditional GMM-based methods in terms of robustness and accuracy under label noise.
