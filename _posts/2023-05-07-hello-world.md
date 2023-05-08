---
layout: post
title: hello world
subtitle: initial post for the Gods Eye development log by K Mills
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [godseye]
---

we recently entered preproduction of the interstitial for the Gods Eye animated series. the animation will run around 2 minutes and introduce some of the core characters for the series. the animation is being created using a mix of solutions, but moho animation tool is the primary animation tool. given the limited resources and abundance of technological advances, we are leverage machine learning to accelerate the efforts. an example of this is the character design. 


## character generation

while i'm a lifelong illustrator and artist capable of creating original characters, i know where my strengths are. additionally there are so many other things that need to be done that producing a reference illustration is only the beginning.

working with Tanya i asked her to provide a virtual casting of people we'd like to cast. i wanted to have a starting point for figuring out the appearance of the characters and starting with images of real people is a perfect option. once she shared a few example images, i jumped into stable diffusion and started to perform CLIP image interrogation on the provided image. this helped generate a prompt describing what stable diffusion sees in the image. using this process i get a pretty verbose prompt, but it's a great starting point for me to optimize it and use in `txt2img` to start generating new "people" based on that description.


