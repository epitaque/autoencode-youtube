# What is this repo?
It's a Jupyter notebook that takes a bunch of YouTube URL's as input, and outputs a video. The output video contains the original (cropped) YouTube video on the left, and that same frame but encoded/decoded by Stable Diffusion's VAE on the right.

https://vimeo.com/781731139

## Why?
To answer the question: how well can the VAE encode frames of a video? No matter what you pass into the unet, you'll be limited by what the VAE can generate.  
In my opinion, the result is not great. Lots of artifacts between frames.