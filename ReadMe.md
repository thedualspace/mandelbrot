## Warning: This code was written before I had learned good coding practices like writing comments, DRY, or writing code that doesn't suck. 
This was a personal curiosity project that ultimately led to me pursuing a formal course in coding, and a career in web development. I didn't know this at the time however, so was writing these scripts only for myself. The fractals generated however were quite mesmerising, so I've incuded the work here in a repo which you can browse if you wish. 

Filenames containing CUDA expect an Nvidia GPU to run. Other files use the standard JIT compiler on the CPU, but this will run more slowly. 

To create videos, the applications produces a series of .png's which are combined using FFMPEG. To generate a 1m 30s video at 1080p 30fps, 2700 frames are required, which took about 1hr 30min on a dell inspiron laptop.

Some images generated are included below:

![psychadelic](/images/psychadelic.png)

![Off-axis Mandelbrot](/images/Mandelbrot.png)