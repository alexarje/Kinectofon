# Kinectofon  #

Version: 	   0.2  
Created date:  2013-01-21  
Modified date: 2013-05-27  

## What can it do? ##

The Kinectofon is an instrument for creating sound from a Kinect sensor device. It is based on turning images into [motiongrams](http://en.wikipedia.org/wiki/Motiongram), which are again turned into sound based on an "inverse-FFT-process". See my [NIME 2013 paper](http://www.arj.no/wp-content/2013/05/Jensenius_2013c.pdf) for details.

## Usage ##

Connect your Kinect sensor, open the patch, start the video input, start the audio, move to make sound. The following keyboard commands can be used: 

    esc = toggle fullscreen mode
    w   = white noise
    p   = pink noise
    
    a   = average
    l   = line
        
    i   = image
    m   = motiongram
        
    1   = Regular image
    2   = Depth image
    3   = Silhouette image
    4   = Foreground image
    5   = Motion image
    6   = Depth motion image
    7   = Silhouette motion image
    8   = Foreground motion image
    
## Requirements ##

- [Max](cycling74.com/products/maxmspjitter/) from Cycling '74
- [Jamoma](http://jamoma.org/)


## More information ##

The Kinectofon was presented in a paper at NIME 2013: 

- Jensenius, A. R. (2013). [Kinectofon: Performing with shapes in planes](http://www.arj.no/wp-content/2013/05/Jensenius_2013c.pdf). In *Proceedings of the International Conference on New Interfaces For Musical Expression*, pages 196–197, Daejeon, Korea.


## Author ##

Alexander Refsum Jensenius --- http://www.arj.no  
University of Oslo, Department of Musicology, fourMs lab


## History ##

v0.2: Updated for NIME 2013, including fullscreen mode and keyboard shortcuts  

v0.1: First working version