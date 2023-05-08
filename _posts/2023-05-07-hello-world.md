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

while i'm a lifelong illustrator and artist capable of creating original characters, i know where my strengths are and to acheive the level of quality i want to reach, i need some help. additionally there are so many other things that need to be done that producing a reference illustration is only the beginning.

working with Tanya i asked her to provide a virtual casting of people we'd like to cast. i wanted to have a starting point for figuring out the appearance of the characters and starting with images of real people is a perfect option. once she shared a few example images, i jumped into stable diffusion and started to perform `CLIP` [image interrogation](https://huggingface.co/spaces/pharma/CLIP-Interrogator) on the provided image. this helped generate a prompt describing what [stable diffusion](https://huggingface.co/spaces/camenduru/webui) sees in the image. using this process i get a pretty verbose prompt, but it's a great starting point for me to optimize it and use in `txt2img` to start generating new "people" based on that description.

![source-reference-2-generated-references]()

after a number of iterations i settled on a starting point to start generating illustrated examples using `img2img` wih the image created in the previous step. similar to generating person examples, it's an iterative process of playing with settings and tweaking your prompts over and over until u find something u desirable. 

![generated-reference-2-generated-illustrations]()

once we find a nice example we can use this to move on to next phase. i like to take the generated art into procreate where i ink and color a clean version. i also start to play with matching a body to the head based on the the chosen proportions. 

