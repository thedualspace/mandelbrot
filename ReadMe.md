# Mandelbrot Visualiser

#### Warning: This code was written before I had learned good coding practices like commenting my code properly, applying DRY principles, or writing code that doesn't suck. 
This was a personal curiosity project that ultimately led to me pursuing a formal course in coding, and a career in web development. I didn't know this at the time however - I was only writing these scripts only for myself, so **they are very messy**. The fractals generated were quite mesmerising, so I've incuded the work here in a repo which you can browse if you wish. 

To create images the famous mandelbrot algorithm is applied to every pixel in a frame placed at specified coordinates and zoom level. The algorithm will return the number of iterations that pixel (rather its coordinate in the complex plane) went through before exceeding a set value. Exceeding this value is taken as diverging to 'infinity'. This value is recorded for every pixel, and allows us to create a grayscale image by normalising the values return by the algorithm.
To add color, standard linear colormaps from matplotlib are used.

![Mandelbrot function](/images/equation.png)

To create videos, the applications produces a series of .png's which are combined using FFMPEG. To generate a 1m 30s video at 1080p 30fps, 2700 frames are required, which took about 1hr 30min on a dell inspiron laptop.

Filenames containing CUDA expect an Nvidia GPU to run. Other files use the standard numba JIT compiler on the CPU, but this will run more slowly. 

Some images generated are included below:

![psychadelic](/images/psychadelic.png)

![Mandelbrot Off-axis](/images/Mandelbrot.png)

![Mandelbrot Octopus](/images/Octopus.png)

![Julia Icicles](/images/juliaIcicles.png)

![Mandelbrot lightning](/images/lightning.png)

![Mandelbrot Blood Cell](/images/Mandelbrot.png)

![Mandelbrot Snowstorm](/images/snowstorm.png)

![Julia](/images/julia.png)

![Mandelbrot Normal Map](/images/normalMap.png)

![Mandelbrot Inferno](/images/mandelbrotInferno.png)
