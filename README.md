# BME_590_Fast_Style_Transfer
By Yuqin Shen. Advisor: Ouwen Huang.

The code implements video style transfer based on image style transfer from the paper 1) **[A Neural Algorithm of Artistic Style
](https://arxiv.org/abs/1508.06576)**, 2) **[Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://arxiv.org/abs/1603.08155)**, 3) **[Instance Normalization: The Missing Ingredient for Fast Stylization](https://arxiv.org/abs/1607.08022)**.

In this repository we provide three jupyter notebook to perform the following:
- Perform Neural style transfer using VGG19 `Neural_style_transfer.ipynb` 
- Transform video using pre-trained checkpoint files `checkpoint_trained.ipynb`
- Train new models and transfer video based on the trained model `train_video.ipynb`

The code work is based on **[Logan Engstrom](https://github.com/lengstrom/fast-style-transfer)**, **[Leo Hu, Chris Zhou](https://github.com/leohu6/BME590-Perceptual-Loss-Style-Transfer)**.


## Video Stylization 
Here we transformed every frame in a video, then combined the results. [Click to go to the full demo on YouTube!](https://youtu.be/n3zKdJ1J-U0) .
<div align = 'center'>
     <a href = 'https://youtu.be/N-BCa48eh8g'>
        <img src = 'data/stylized/Fast_style_transfer_new.gif' alt = 'Stylized fox video. Click to go to YouTube!' width = '711px' height = '400px'>
     </a>
</div>
