# GAN_Waifu_Generator
A Generative Adversarial Network trained on a dataset of over 60,000 anime girl images to generate new ones. Based on the original model proposed by Goodfellow et al. in the paper "Generative Adversarial Networks", this model simultaneously trains both a generator to create new images and a discriminator to distinguish between the generated images and the real images. Subsequently, the generator then is able to create accurate waifu images which, if you use them as profile pictures as often as I do, is a big help.

## Dataset

Unfortunately I couldn't find the link to the original source of the 60,000 waifu images (;-;). However, the dataset is essentially comprised of 63633 square images of anime girl faces of different resolutions. All of them were resized to be 64x64 when training the model. 

## Sample Results

### Single Images

### Groups of Images

## Acknowledgments
Generative Adversarial Networks by Goodfellow et al.: https://arxiv.org/pdf/1406.2661.pdf

Training code based off of Nagesh Singh Chauhan's: https://www.kdnuggets.com/2020/03/generate-realistic-human-face-using-gan.html
