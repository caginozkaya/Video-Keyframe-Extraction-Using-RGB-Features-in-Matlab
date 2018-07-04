# Video-Keyframe-Extractor-Using-RGB-Features-in-Matlab

In this script, i use a sample video called planes.mp4 which has 4 scene changes. If you watch the video you can see that there are scene changes at approximately:
1)00:03:xx
2)00:05:xx
3)00:10:xx
4)00:14:xx

-It takes the i th and i+1 th frames' RGB features and calculates the histogam difference of those features. 
In the figure the maximum points of the graph are the maximum changes of RGB features which extracted from the frames. 


<a href="https://ibb.co/hEpyNJ"><img src="https://preview.ibb.co/dFc7Gd/extract.png" alt="extract" border="0"></a><br /><a target='_blank' href='https://poetandpoem.com/James-Devaney'>James Devaney biography</a><br />

-As you can see in the figure, you can take the maximum points of the graph as keyframes. It finds all 4 keyframes successfully in this example.

-planes.mp4 is stored as 30 fps so you can get the duration of the maximum change by dividing the frame no of those maximum points by 30.
