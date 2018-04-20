# BIL Coding Style (BCS)

## 1. Clarity over efficiency
We have more interest in **algorithm** than **implementation**. 
Of course, writing an efficient code is a very import skill.
But, we need more **flexible** code that are to be **shared**. So, first priority is **readibility**!

1.2 Comment, comment, and more comment

Before writng any block of code, wrie comments first. 
Check logics based on the commnents. See that you're not missing any step of your algorithm. Take time to consider different structures, data structures, or algorithm itself.

When you are confident that this block would work, (only after that) you can write up actual code (C++, Python, Matlab, R, etc.).

1.3 Functions and classes must have block comments

Without carefully written comments, functions or classes are useless.

An example: 
```
def detectFaceUsingCNN: 
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
```


2. Name maters

2.1 Function names start with lower case letters while class names start with capital letters.

2.2 Function name should be “active”
A function performs a very specific action. 
Use the **verb** that best describes the core action of the function. 

Examples: 

```
estimateTheta(...)

projectOntoH(...)

calculateMeanAndVariance(...)
```


3. Quality over quantity

Let’s produce high-quality code that can be used 
