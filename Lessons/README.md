# Lessons

## Week 1: Not All ML is DL

![equation](https://latex.codecogs.com/png.download?DL%5Csubset%20ML%5Csubset%20AI)

Someday this course will occur after other machine learning (ML) courses in a multi-course sequence. It was by the request of the Data Science program that we focus on DL here, which I was happy to do, because DL is what I know best. 

Still, we're going spend some time reviewing some key topics that appear in non-DL ML since they form the basis of what will come next.

### Structured Data and Features

The kinds of data that many businesses deal with are already highly structured, such as having a set of columns in a spreadsheet which each describe aspects of a data item (or "data point").  For housing data, a given row in a spreadsheet might tell you various "features" of a house such as its zip code, last selling price, and...IDK, more housing-related stuff.   Or perhaps you have a dataset on people, and the columns in each row make up a data point for one person, describing "features" about them their height, weight, age, gender, whether or not they are a smoker, and so on. 

These features are often highly descriptive and immediately useful for traditional machine learning systems such as Random Forests models -- business-based ML engineers get a lot of mileage out of Random Forests, by the way (because, again, they're often working with highly-structured, spreadsheet-like data).  We're not going to cover those models in this course, but we mention them here to note that

>  If you've already got highly meaningful features for your data, you don't "need" neural networks (NNs).

You *could* use a NN (and we'll do examples using NNs) but you could just as easily -- more easily, even! -- start with something simple like a linear model  (statisticians get a lot of mileage out of linear models BTW) or a Random Forest ,and that would be a traditional approach which works very well and makes people lots of money. 

But... 

What if you don't have well-defined features?  What if you want to extract information from images, or audio, or raw text?

**Then you still don't "need" a NN!** Plenty of feature-extraction techniques have been developed over the decades to find important aspects of images, audio, text, and more, and then feed these into traditional ML or stats-based models!  An example you might be familiar with would be face-detection algorithms for camera-based apps: these don't need NNs to find out where your eyes & nose & mouth are!  And they can execute very quickly.  

Here's a video of me being silly, using a (non-NN) "face detector" algorithm which acts an input to a ML algorithm that controls the pitch of an audio oscillator:

<iframe width="560" height="315" src="https://www.youtube.com/embed/j8S9Cx0xnbs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



**TODO: SAY MORE**

### Not all NNs are DNNs

The simple neural networks (NNs) we will start with will not be "deep" neural networks (DNNs); "deep" refers to having many "layers" of artificial neurons.  Advances in algorithms over the past two decades have made it feasible to train very deep networks -- sometimes having thousands of layers -- which previously were an impossibility. As a [heuristic], we can think of "earlier" layers and being feature extractors for "later" layers, where the former are closer to the inputs and the latter are closer to the outputs. 





