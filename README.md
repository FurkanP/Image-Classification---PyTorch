# Pytorch

PyTorch is an open-source machine learning library for Python, fully based on Torch. It is primarily used for applications such as natural language processing (NLP). PyTorch is a redesign and implementation of Torch in Python, while sharing the same core C libraries for backend functionality. The developers of PyTorch have optimized this backend code to run efficiently in Python. They also retained the GPU-based hardware acceleration and extensibility features that made Lua-based Torch popular.




## Convolutional Neural Net

A Convolutional Neural Network (ConvNet/CNN) is a deep learning algorithm that can take an input image, assign importance (learnable weights and biases) to different objects or features within the image, and distinguish one from another. The pre-processing required for a ConvNet is much lower compared to other classification algorithms. While traditional methods rely on hand-engineered filters, ConvNets have the ability to learn these filters/characteristics with enough training. The architecture of a ConvNet is inspired by the connectivity pattern of neurons in the human brain, particularly modeled after the organization of the visual cortex. Individual neurons respond to stimuli in a restricted area of the visual field, known as the Receptive Field. A collection of these fields overlaps to cover the entire visual field.




## Code Description


    File Name: Main.py
    File Description: Main class to initiate the model training lifecycle.


    File Name : CNN.py
    File Description: Class defining the structure of the Convolutional Neural Network (CNN).    

    File Name : TrainModel.py
    File Description : Code for training and evaluating the PyTorch model.


    File Name : CreateDataset.py
    File Description : Code for loading and transforming the dataset.
    



## Steps to Run

There are two methods to execute the end-to-end workflow:

-Modular Code
-IPython 

### Modular code

-Create a virtual environment.
-Install the required packages: pip install -r requirements.txt
-Run the code: python Engine.py
-Check the output for all visualizations.

### IPython 

Follow the instructions in the notebook `CNN.ipynb`
