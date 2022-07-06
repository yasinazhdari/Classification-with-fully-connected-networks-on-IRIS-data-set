# Intro-to-Tensorflow !!!-Simple Classifications with fully connected and Convolutional networks on simple data sets-Plus tensorflow installation and activation Guide
# Powered By Google Colab
Implementation of  classifiers based on fully connected and Convolutional networks on some simple data sets are considered.
Any comments or recommendations on performance improvement is appreciated.

# if you are going to run tensorflow based codes on your own computer (like jupyter notebook), and you don't have it installed, you can follow this instructions:
1- Download Anaconda from its website (https://www.anaconda.com/products/individual#Downloads) and install it (skip this stage, if you have it already installed).<br />
2-open Anaconda prompt (By searching it from the start menu)<br />
3-inorder to install cpu-based or gpu-based (recommended) tensorflow, use one of the following line of commands in the prompt respectively:<br />
conda create -n tf tensorflow<br />
conda create -n tf-gpu tensorflow-gpu<br />
4-after the download and installation process (about 1.~ GBs size), first activate the corresponding environment (which has the tensor flow) with following command in prompt:<br />
conda activate tf or conda activate tf-gpu (for recommended GPU-based case)<br />
5-after activating the tensorflow-based environment, type "jupyter notebook" in the prompt to open jupyter notebook through your default web browser.<br />
6- open a new notebook and test that you have correctly installed tensorflow by executing following lines of codes:<br />
import tensorflow as tf<br />
tf.__ver__<br />
7-Congrats! You Made it<br />
# Yasin Azhdari<br />
