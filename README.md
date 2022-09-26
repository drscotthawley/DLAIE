# Deep Learning & AI Ethics (DLAEI) Course 


## Welcome 

Welcome to the GitHub repo of the course "Deep Learning &amp; AI Ethics" course taught taught at Belmont University in Fall 2022!  This course includes an "embedded ethics" pedagogical approach in which we will build DL systems, probe them to try to understand how they work, and investigate their ethical implications.  


### **Course Description:**  

This course presents an overview of current machine learning techniques and applications, with particular attention to deep neural network models. Applications will include computer vision, audio signal processing, and natural language processing, for tasks such as classification and regression, and generative models. We will learn how these systems work, and will write code to train them and to probe their outputs and behavior. As an integrated part of the course, we will give attention to issues of ethics & society in training and deploying such models, issues including bias, transparency and accountability. 

#### [Syllabus Link](https://www.dropbox.com/s/al0gaiehleqfhmt/HawleyS_PHYBSADSC4420_Fall2022.pdf?dl=0) (PDF)

### **Instructor:** 

[Scott H. Hawley](https://hedges.belmont.edu/~shawley) 

### **Prerequisite:** 

[Some Python coding proficiency](https://www.learnpython.org/). (cf. ["Lesson 2: Python/Jupyter Review"](https://github.com/drscotthawley/DLAIE/blob/main/Lessons/2_PythonReview.ipynb))

### Textbooks:

We will mostly be using web links, videos, and lecture notes.  The following will serve as textbooks:

#### Required: 

* [Hello World: Being Human in the Age of Algorithms](https://wwnorton.com/books/Hello-World) by Hannah Fry.  This is an accessible and engaging survey of AI technology and ethics.  It is non-technical though. For technical references (again, beyond lecture notes and web links) we may refer to these supplemental textbooks:

#### Supplemental:

As technical references, three excellent FREE online textbooks are:

* [Neural Networks and Deep Learning](http://deeplearningandneuralnetworks.com/) by Michael Nielsen.
* [Deep Learning](https://www.deeplearningbook.org/) by Ian Goodfellow, Yoshua Bengio, and Aaron Courville.
* [The FastAI Book, aka "fastbook": "Deep Learning for Coders with Fastai and Pytorch: AI Applications Without a PhD"](https://github.com/fastai/fastbook) by Jeremy Howard & Sylvain Gugger. This is written entirely as executable Jupyter notebooks.


## Overall Plan

* **Schedule:** This *draft* version of the course will be all on your own & asynchronous, but planned according to the synchronous MWF (Monday-Wednesday-Friday) schedule of the final version of the course.  M&W will tend to focus on math & coding lessons, and Fridays being for ethics topics.  (In the final course, Lessons will be "on your own"/asynchronous readings, videos, quizzes, and assignements, and Ethics Discussion meetings will be synchronous via Zoom.)  

* **Deep Learning framework:** We'll start with raw [NumPy](https://numpy.org/), then for most of the course we'll use [PyTorch](https://pytorch.org/) with some [fastai](https://github.com/fastai/fastai) on top (for convenience). 
* **Assignments:** You'll write coding assignments using online "notebook" hosting platforms [Colab](https://colab.research.google.com) or [Gradient](https://gradient.paperspace.com/), which give *GPU access for free* so you won't need your own GPU. The assignments contain instructions, boilerplate code, and "fill in the blank" areas, along with sample test outputs so you can check your work as you go. When you are finished, you'll use a Google Form to submit the "sharing URL" for your notebook. Then *periodically*, a server app will download any updated notebooks and run the assignment's "test suite" against them. You will then receive an email of your score, i.e., how many tests passed.
* **Quizzes:** For the draft version of this course, grades will not be issued for quizzes. In the final version, quizzes will be on Blackboard. 



## Lessons

See the [Lessons](Lessons/) area.  These go with [companion videos on YouTube](https://www.youtube.com/playlist?list=PLobhwAFRfHjDLcvyy2nB75CzeDa7gLQ09).

Direct links to notebook below (can also be found in the Lessons area):

1. [Not All ML is DL](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/01_NotAllMLisDL.ipynb)  
1. [Python Review](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/02_PythonReview.ipynb)  
1. [NNs Fit Curves](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/03_NNsFitCurves.ipynb)  
1. [Problematic Image Analyzer](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/04_ProblematicImageAnalyzer.ipynb)
1. [Coding Logistic Regression](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/05_Coding_Logistic_Regression.ipynb)
1. [ConvNets](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/06_ConvNets.ipynb)
1. [NLP via HuggingFace Transformers](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/07_NLP_via_HuggingFace_Transformers.ipynb)
1. [DeepNLP](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/08_DeeperNLP.ipynb)
1. [Audio](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/09_Audio.ipynb)
1. [Backprop](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/10_Backpropagation.ipynb)
1. [Tabular Spotify](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/11_Tabular_Spotify.ipynb)
1. [Autoencoders, Unets, Skips, and ResNets](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/12_Autoencoders_UNets_Skips_ResNets.ipynb)
1. [GAN Overview](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/13_GAN_Overview.ipynb)
1. [SampleNN Bias and CE](https://colab.research.google.com/github/drscotthawley/DLAIE/blob/main/Lessons/XX_SampleNN_2_Bias_and_CE.ipynb)


## Assignments

See the [Assignments](https://github.com/drscotthawley/DLAIE/tree/main/Assignments) area.


## Licence
These materials are governed by [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/). You may use them, with attribution, for non-commercial purposes.  As [Francois Fleuret says](https://fleuret.org/dlc/#license), "More simply: I am okay with this material being used for regular academic teaching, but definitely not for a book / youtube loaded with ads / whatever monetization model I am not aware of."


## Acknowledgements
See [Acknowledgements](Acknowledgements.md)



---

(c) Scott H. Hawley, 2021, 2022.
