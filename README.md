# Winter 2023 SYDE 552 Tutorials
This repository has the collection of Jupyter notebooks used for tutorials in the Winter 2023 offering of BIOL487/SYDE552: Computational Neuroscience at the University of Waterloo. The course was instructed by [Dr. Bryan Tripp](https://uwaterloo.ca/systems-design-engineering/profile/bptripp) and [Trevor Yu](https://github.com/trevor-yu-087) was the teaching assistant. The course covers topics in both neuroscience and deep learning, in particular, how computational methods in deep learning are related to neuroscience concepts. As the course was being reworked for this offering, new tutorial content was also developed. Tutorial 6 was developed by Bryan and the rest by Trevor.

This set of tutorials focuses on developing practical skills related to machine learning in Python and using PyTorch to implement and train various neural network models discussed throughout the course. The following is a list of tutorial topics:
1. Linear regression in scikit-learn
2. Multi-layer perceptron (MLP) and neural network training in PyTorch
3. Understanding the convolution operation in PyTorch
4. Convolutional neural networks (CNN) in PyTorch
5. Recurrent dynamics and LSTM networks in PyTorch
6. Transformer networks in PyTorch and using Hugging Face transformers
7. Q-learning using the gymnasium reinforcement learning (RL) environment

Although the lecture content for the Winter 2023 course offering cannot be released here, lecture videos from a previous offering of SYDE 552 can be found on the [linked YouTube playlist](https://youtube.com/playlist?list=PLX-XEf1yTMrkcpni8RJMnqGBlA9uEHlaE). That course was taught by Dr. Terry Stewart and Dr. Michael Furlong and has a different curriculum.

## Usage
The tutorial exercises were designed for students who have a basic programming background but may not be familiar with machine learning. A background in the Python programming language, numeric computing (e.g. numpy, MATLAB, R, Julia), and linear algebra would be assets in being able to complete the tutorials independently.

The `tutorial` notebooks are intended to be shared with the class as a fill-in tutorial activity, while the `complete` notebooks serve as example solutions. Most notebooks have links to relevant documentation that will assist with the solution. All `complete` notebooks should be able to run end-to-end, provided the filepaths are correct and all dependancies are installed.

Tutorial 6 references some data that is too big to upload onto Git. If you are interested in obtaining the data to run this example fully, please contact Trevor via email: [trevor.yu@uwaterloo.ca](mailto:trevor.yu@uwaterloo.ca).

## Environments
All the notebooks should be able to run in Google Colab, though additional packages will need to be installed as noted in commented cells. In addition, the data for tutorials 1 and 6 may need to be uploaded and filepaths adjusted. To use the GPU to run tutorial 6, Colab will need to be configured with a GPU-enabled runtime.

If you want to run the files in a local virtual environment, you can use the `requirements.txt` file to install all dependancies. Note that if you intend to use a GPU or are using a Mac, you should visit [pytorch.org](https://pytorch.org) for latest install instructions for your system.

All examples were developed with Python 3.8.10 and torch 1.12.