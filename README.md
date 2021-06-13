# CLIP-VGG19-style-transfer

Style transferring using VGG 19 and OpenAI's CLIP.

In normal style transfer gram matrix is used to transfer style but here we can use CLIP model.

Total loss is can be defined as

Loss = Content loss + CLIP loss + Total variation loss

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://bit.ly/3gpEiCO)

Text prompt  "a starry night style painting" used to produce the below output

![starry night output](/output/styled_starry_night.png)
