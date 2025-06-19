Poorna Chander Oruganti - 700771980

# Question Answering with Transformers

Used Hugging Face’s transformers library to build a simple question answering system using pre-trained models.

# Conditional GAN on MNIST

A PyTorch implementation of a Conditional Generative Adversarial Network (cGAN) that generates MNIST digits conditioned on class labels.

## Features
- Generates MNIST digits 0–9 based on input labels  
- Simple MLP-based Generator and Discriminator  
- Training loop with BCE loss and Adam optimizer  
- Visualization of generated digits in a single row  

## Requirements
- Python 3.7+  
- torch  
- torchvision  
- matplotlib  

## Setup & Installation
```bash
git clone https://github.com/your-username/cgan-mnist.git
cd cgan-mnist
pip install torch torchvision matplotlib
```

## Usage

### Google Colab
1. Open the provided `cGAN_MNIST.ipynb` notebook in Colab.  
2. Run each cell in order to train the model and visualize results.

### Local
1. Ensure dependencies are installed (see **Requirements**).  
2. Run the training script:
   ```bash
   python train_cgan.py  # or run the cells in your own notebook
   ```
3. After training, generate a row of digits (0–9) with:
   ```bash
   python generate_samples.py
   ```


```


## References
- [Conditional GANs paper (Mirza & Osindero, 2014)](https://arxiv.org/abs/1411.1784)  
- MNIST dataset  

## License
This project is released under the MIT License.
