# nvdiffrec Colab version for those without gpu or on the move
My Colab version of exciting new nvdiffrec from  Nvidia
https://github.com/NVlabs/nvdiffrec
![image](https://user-images.githubusercontent.com/1938534/169154788-cfa6f914-1320-40e7-81ed-839ae95413a7.png)

What is new is that it is now able to extract and remove environment lighting from texture. so env lighting is no longer baked in texture, and objects can finally be animated moved under your own lighting.
Something that was holding nerf textured mesh outputs back in the past.

As for any questions regarding how to do this or that you will be best served in issues section of authors. I created this just jesterday and was able to run just run included demo dataset yet.

As for how to create custom dataset for to reonstruct from your own images. My guess asking in issues section in authors github will be much faster and better answer. but for now i guess. following https://github.com/sxyu/svox2 how to do custom nerf dataset using colmap could work too. I will try this today and update repo with what I found. 

Sadly this algo requires you to provide masks in alpha of images (like it is done in synthetic nerf datasets)  as this mask detection is not part of this algo pipeline yet.

![image](https://user-images.githubusercontent.com/1938534/169155045-7a7961ae-fb0a-40b8-8d47-abb72fd0a367.png)
just look at that texture purity ;D yay 
![image](https://user-images.githubusercontent.com/1938534/169155123-662b9355-7de6-4fec-91b7-ad85735b268e.png)


