# CLIP-VGG19-style-transfer (experiment)

Style transferring using VGG 19 and OpenAI's CLIP.

In normal style transfer gram matrix is used to transfer style but here we can use CLIP model.

Total loss is can be defined as

Loss = Content loss + CLIP loss + Total variation loss

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://bit.ly/3gpEiCO)

Text prompt  "a starry night style painting" used to produce the below output

![starry night output](/output/styled_starry_night.png)


https://user-images.githubusercontent.com/3255994/121798497-4c026580-cc44-11eb-8c84-1b66e56cee59.mp4


## References 

[1] [CLIP style transfer ](https://github.com/Zasder3/CLIP-Style-Transfer)\
[2] [CLIP](https://openai.com/blog/clip)\
[3] [Total variation denoising](https://en.wikipedia.org/wiki/Total_variation_denoising)

