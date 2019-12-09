# BME_590_Fast_Style_Transfer
By Yuqin Shen. Advisor: Ouwen Wang.

The code implements video style transfer based on image style transfer from the paper 1) **[A Neural Algorithm of Artistic Style
](https://arxiv.org/abs/1508.06576)**, 2) **[Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://arxiv.org/abs/1603.08155)**, 3) **[Instance Normalization: The Missing Ingredient for Fast Stylization](https://arxiv.org/abs/1607.08022)**.

In this repository we provide three jupyter notebook to perform the following:
- Perform Neural style transfer using VGG16 
- Transform video using pre-trained checkpoint files 
- Train new models and transfer video based on the trained model

The code work is based on **[Logan Engstrom](https://github.com/lengstrom/fast-style-transfer)**, **[Leo Hu, Chris Zhou](https://github.com/leohu6/BME590-Perceptual-Loss-Style-Transfer)**.


## Video Stylization 
Here we transformed every frame in a video, then combined the results. [Click to go to the full demo on YouTube!](https://youtu.be/N-BCa48eh8g) .
<div align = 'center'>
     <a href = 'https://youtu.be/N-BCa48eh8g'>
        <img src = 'data/content/movie/stylized_movie/dance_stylized_vgg16_0.mp4' alt = 'Stylized fox video. Click to go to YouTube!' width = '800px' height = '400px'>
     </a>
</div>
