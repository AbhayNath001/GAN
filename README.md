# GAN - Generative Adversarial Network

<h2>Overview</h2>
This repository contains the code and documentation for a Generative Adversarial Network (GAN) implemented using TensorFlow. The GAN consists of a generator and a discriminator model. The generator creates new images, while the discriminator is trained to distinguish between real and generated images. This project uses the Fashion MNIST dataset for training and generating images.

<h2>Table of Contents</h2>

- [Introduction](Introduction)
- [Installation](Installation)
- [Usage](Usage)
- [Data Preprocessing](Data_Preprocessing)
- [Generator and Discriminator](Generator_and_Discriminator)
- [Training](Training)
- [Monitoring](Monitoring)
- [Results](Results)
- [Model Saving](Model_Saving)
- [Contributing](Contributing)
- [License](License)

## Installation
Before running the code, you will need to install the required dependencies. You can use the following command to install them:
`pip install tensorflow tensorflow-gpu matplotlib tensorflow-datasets
`
## Usage
To use this GAN for generating images, you can follow these steps:

Clone this repository to your local machine:
`git clone https://github.com/your-username/gan.git
`
Change directory to the repository:
`cd gan
`
Run the Jupyter Notebook or Python script to execute the code.
## Data Preprocessing
The Fashion MNIST dataset is used for training the GAN. The data is preprocessed, scaled, and transformed before being used for training. The code includes functions for data scaling and preprocessing.

## Generator and Discriminator
The GAN consists of a generator and discriminator model. The generator creates new images, while the discriminator is responsible for distinguishing between real and generated images. These models are implemented using the TensorFlow Keras API.

## Training
The training process is implemented using the custom FashionGAN class, which extends the TensorFlow Model class. The generator and discriminator are trained in an adversarial manner. The training process includes loss calculations and backpropagation.

## Monitoring
The ModelMonitor callback class is used to save generated images during training. These images are saved in the "images" directory and can be used to monitor the progress of the GAN.

## Results
After training, you can visualize the generated images and assess the quality of the generated content. The results are stored in the "images" directory.

## Model Saving
The trained generator and discriminator models can be saved using the save method from TensorFlow's Keras API. The saved models can be loaded and used for generating new images.

## Contributing
If you'd like to contribute to this project, please fork the repository, create a new branch, make your changes, and submit a pull request. Contributions, bug reports, and feature requests are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.
