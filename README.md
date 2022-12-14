# ray-march-fractals-cuda
An exploratoin program to render the Mandelbox using a ray marching algorithm. Coded with C++ and CUDA to minimize render times

## Demo Images
![Demo Image 1](out4.png)
![Demo Image 2](out2.png)
![Demo Image 3](out5.png)
![Demo Image 4](out6.png)
![Demo Image 5](out3.png)

## Attribution and Dependencies
The program uses the stb_image_write header file (from https://github.com/nothings/stb) 
to save renders as images. You must download the file and place it in the `main` directory
to run the program.

The Mandelbox distance estimator algorithm was translated and modified from the [Syntopia blog](http://blog.hvidtfeldts.net/index.php/2011/11/distance-estimated-3d-fractals-vi-the-mandelbox/).
