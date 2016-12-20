#**Finding Lane Lines on the Road** 
<img src="laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

When we drive we use visual cues to know where to steer the car, if we should increase or decrease our speed or stop altogether. One of the most powerful aids we have when we drive are the line lines. So, the focus of this project is to develop a very simple model to detect lane lines, both in static images as well as in videos.

**Step 1:** Getting setup with Python

If you want to run this project, you will need Python 3 along with the numpy, matplotlib, and OpenCV libraries, as well as Jupyter Notebook installed. 


**Step 2:** Installing moviepy  

In this project we use "moviepy" package for processing video in this project. To install moviepy run:

`>pip install moviepy`  

and check that the install worked:

`>python`  
`>>>import moviepy`  
`>>>`  
(Ctrl-d to exit Python)

**Step 3:** Opening the code in a Jupyter Notebook

You can explore the code that's in the Jupyter Notebook. You're more than welcome to play around with the values an see how this affect the pipeline. In order to run the Notebook, `cd` into the root of this project and run: 

`> jupyter notebook`

A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook.
