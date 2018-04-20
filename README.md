# BIL Coding Style (BCS)

## 1. Clarity over efficiency
We have more interest in **algorithm** than **implementation**. 
Of course, writing an efficient code is a very import skill.
But, we need more **flexible** code with which we can play with data and develop ideas.
So, first priority is **readibility**. 
If someone else may want to use your code, it must be readabile. 

### 1.1 Comment, comment, and more comment

Before writng any block of code, wrie comments first. 
Check logics based on the commnents. See that you're not missing any step of your algorithm. 

Take time to consider alternative steps, data structures, or algorithms.

When you are confident that this block would work, (only after that) you can write up actual code (C++, Python, Matlab, R, etc.).

### 1.2 Functions and classes must have block comments

Without carefully written comments, functions or classes are useless.
Block comments with detail information must always come at the beginning.

An example: 
```
def detectFaceUsingCNN(img, model, scale): 
    """
    multi-view face detector using CNN.
    (SOME MORE DETAILS).
    
    input: 
        img - input image
        model - CNN model
        scale - scale parameter
    output:
        rect - list of rects containing faces, format: (x, y, w, h) 
        ellipse - list of ellipses containing faces, format: (x, y, a, b) 
        pose - 3D pose of the detected face
    """
```


## 2. Name maters

### 2.1 Function names start with lower case letters while class names start with capital letters.

### 2.2 Function name should be “active”
A function performs a very specific action. 
Use the **verb** that best describes the core action of the function. 

Examples: 

```
estimateTheta(...)

projectOntoH(...)

calculateMeanAndVariance(...)
```


## 3. Quality over quantity

Let’s produce high-quality code that can be re-used by (of course) yourself and others!

### 3.1 Test

When you implement a module, write a test code with it. 
Let someone else to use the test code to make sure the module works in a wide range of circumstances.


### 3.2 Use `assert` as often as possible

When coding, do not trust yourself. Simple (and stupid) mistakes are your worst enemy!

See [here](https://wiki.python.org/moin/UsingAssertionsEffectively) for more information.

### 3.3 Develop debugging skills

Good software engineers are good at debugging!

Study the Python debugger ('pdb') [link](https://docs.python.org/3/library/pdb.html) and use if for your everyday coding.
It's going to be your best friend!

Another good tutorial is [here](https://www.digitalocean.com/community/tutorials/how-to-use-the-python-debugger).

