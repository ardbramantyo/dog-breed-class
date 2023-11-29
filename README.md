# Dog Breed Classification Project

This project focuses on classifying dog breeds using Convolutional Neural Networks (CNNs). The goal is to correctly identify the breed of a dog from images, even if the breed is misclassified. The project involves the use of three different CNN model architectures: ResNet, AlexNet, and VGG.
Overview

The primary objectives of the project are as follows:
 - Correctly identify which pet images are of dogs, regardless of the breed.
 - Correctly classify the breed of dog for the images that are indeed dogs.
 - Evaluate and compare the performance of three CNN model architectures: ResNet, AlexNet, and VGG.

## Getting Started
### Installation

To set up the project locally, follow these steps:

bash

# Clone the repository
git clone https://github.com/ardbramantyo/dog-breed-class.git

# Change into the project directory
cd dog-breed-class

# Install dependencies
pip install -r requirements.txt

### Usage

The main script check_images.py is used for classifying pet images. Example usage:

bash

### Run the main script
python check_images.py --dir pet_images/ --arch resnet --dogfile dognames.txt

To classify uploaded images, use the following script:

bash

### Classify uploaded images using all three models
sh run_models_batch_uploaded.sh

Training Your Own Models

If you wish to train your own models, detailed instructions can be found in the project documentation.
Results and Evaluation

After running the classification on uploaded images, review the results files (resnet_uploaded-images.txt, alexnet_uploaded-images.txt, vgg_uploaded-images.txt) to answer specific questions about the breed classification.
Dependencies

    Python 3.x
    Required libraries (listed in requirements.txt)

License

This project is licensed under the MIT License.
