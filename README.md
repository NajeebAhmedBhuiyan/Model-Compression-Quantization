In this repository, 📚 I will be delving into the concept of quantization, which serves as a pivotal method for compressing deep learning models. 

[Quantization](https://pytorch.org/docs/stable/quantization.html) involves the process of reducing the precision of numerical representations within a model, thereby decreasing its computational and memory requirements while maintaining performance. By mapping weights and activations to a reduced set of discrete values, quantization optimizes model efficiency without significantly compromising accuracy.

This repository holds particular significance for individuals who have developed and trained their models using `PyTorch` and are seeking efficient methods to compress and optimize them. Through the exploration of different quantization techniques, such as *Post-Training Quantization*, *Quantization Aware Training* etc. 🚀

In the python notebook of *Post-Training Quantization*, I trained the model with [Tuberculosis (TB) Chest X-ray Database](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset) from Kaggle and then I have quantized the model. After quantizing the model, it reduced to 8MB from 32MB without affecting the accuracy that much. All these were implemented using PyTorch.

Still to upload the notebook on *Quantization Aware Training*.

Happy Studying!

The rosources were used in creating the notebooks are given below:
1. [Quantization Documentation](https://pytorch.org/docs/stable/quantization.html)
2. [PyTorch Blog on Quantization](https://pytorch.org/blog/introduction-to-quantization-on-pytorch/)
3. [Quantization Notes by Umar Jamil](https://github.com/hkproj/quantization-notes)
