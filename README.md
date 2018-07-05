# Video-Keyframe-Extractor-Using-RGB-Features-in-Matlab

In this script, I use a sample video called planes.mp4 which has 4 scene changes. If you watch the video you can see that there are scene changes at approximately:

1)00:03:xx

<a href="https://ibb.co/czKZUy"><img src="https://preview.ibb.co/hOP19y/1.png" alt="1" border="0"></a>

2)00:05:xx

<a href="https://ibb.co/ko0SGd"><img src="https://preview.ibb.co/cxLipy/2.png" alt="2" border="0"></a>

3)00:10:xx

<a href="https://ibb.co/bvDshJ"><img src="https://preview.ibb.co/mx4yNJ/3.png" alt="3" border="0"></a>

4)00:14:xx

<a href="https://ibb.co/iWTshJ"><img src="https://preview.ibb.co/dF6Opy/4.png" alt="4" border="0"></a>

-It takes the i th and i+1 th frames' RGB features and calculates the histogam difference of those features. 
In the figure the maximum points of the graph are the maximum changes of RGB features which extracted from the frames. 


<a href="https://ibb.co/n9rmuy"><img src="https://preview.ibb.co/mNYzEy/extract.png" alt="extract" border="0"></a>

-As you can see in the figure, you can take the maximum points of the graph as keyframes. It finds all 4 keyframes successfully in this example.

-x-axis indicates the duration of the video, by taking the durations of the maximum points you can extract that frame at that duration as keyframe.
