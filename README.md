# HW4 Spring 2023

**Due Wednesday 4/19 11:59 PM Eastern.**

## Walkthrough Video
[**HW4 Walkthrough Video**](https://youtu.be/RFmqw3YTRnc)

## Instructions

In this homework you will work through the following two problems:
1. Iterative Learning Control (ILC) for a car as it avoids an obstacle. 
2. Making a robot walk with hybrid trajectory optimization with a pre-determined contact sequence.

## Submission 

Use any method you like to export your jupyter notebook as a PDF (with all the cell outputs shown), and submit on gradescope. Here are some methods for creating this PDF: [https://mljar.com/blog/jupyter-notebook-pdf/](https://mljar.com/blog/jupyter-notebook-pdf/). 

## Notes 

- These questions will have long outputs for each cell, remember you can use `cell -> all output -> toggle scrolling` to better see all of the output without having to scroll. 

- IPOPT can take a long time for certain problems. In Jupyter Notebooks, IPOPT will not output anything until IPOPT is finished. If you find that IPOPT is hanging for a long time, it may be that IPOPT is running and taking a very long time (which likely means something else is wrong). To see the output of IPOPT in real time, you have to call the script from the Julia REPL. To do this, you can run the following in the REPL:

```julia 
using NBInclude
@nbinclude("Q1.ipynb")
```

## Version History

As bugs show up, they will be addressed on both Piazza as well as this readme.
