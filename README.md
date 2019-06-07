# Hands-on-Tech (HOT) Days @ Georgia Tech Day Camp - Machine Learning Module

_Instructors:_ Mark Davenport (mdav@gatech.edu) & Eva Dyer (evadyer@gatech.edu)<br>
_Teaching assistants:_ Aishwarya Balwani (abalwani6@gatech.edu), Max Dabagia (maxdabagia@gatech.edu), Erik Jorgensen (ejorgensen7@gatech.edu)

### Overview of concepts
- _Image manipulation:_ Show how to use Python to perform some basic image editing (crop, adjust brightness, flip, isolate color channels, etc), as well as introducing noise into an image and then using median filtering to recover the original image.
- _Image convolution:_ Show how using different kernels can do interesting things to an image (e.g. blur, edge detection, etc)
- _Style transfer:_ the aim is to show students how neural networks can transform an input image to be in the style of a certain artist

### Schedule
- Overview and Welcome (5 minutes)
- Walking through the notebook (30 minutes)
- Small group sandbox to explore the concepts (1 hour)
  - explore notebook, play with variables and parameters (10 minutes)
  - decide on idea to pursue, find group to merge with (5 minutes)
  - work on mini-project (45 minutes)
- Compile results and images, create small exhibit of your art and creations! (15 minutes)
- See-and-share other students’ galleries! (10 minutes)

### Ideas for mini-projects (questions to explore):
- What if you add noise to an image and then apply style transfer? How will model interact with different types of objects/ artifacts added to your image?
- How does the model interact with different types of images? What does it seem to be picking up in images when it transforms them?
- What happens to an image if style transfer is applied more than once? What about different styles?
- How does modifying an image before applying style transfer (flipping it, resizing it, dropping color channels, etc) affect the output? Is this the same as applying style transfer and then modifying it with the same operation?
- There are lots of other edge detection filters out there - how do some of them compare to the sobel filters? (Check out filters like Laplace, Prewitt, Scharr, and more! - take a look at https://scikit-image.org/docs/dev/api/skimage.filters.html for more ideas.)
- Are there certain types of filters that could cancel each other out? What might happen if you blur an image and then sharpen it? What happens if you repeat this process lots of times?
- What happens if you modify only certain color channels in an image? Try filtering different combinations of the R,G,B channels with different filters - what effects does this have on different images?
- Is there a way to quantify how close the new image is to the style/content images? Which one is it closer to? 

________________________________________

**[Click here to learn how to run this notebook in Google Colaboratory](https://docs.google.com/document/d/1ILbefxjt_mY8vE4lt_iqjOldU0poZB4gw9qphEWLOck/edit?usp=sharing)**

________________________________________

**Contributors:**
- Aishwarya Balwani (abalwani6@gatech.edu) 
- Max Dabagia (maxdabagia@gatech.edu) 
- Eva Dyer (evadyer@gatech.edu)
- Erik Jorgensen (ejorgensen7@gatech.edu)


![](https://gph.is/g/E008Qmy)
