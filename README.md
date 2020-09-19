# DeepCreamPyLab
*Decensoring Hentai with Deep Neural Networks on Google Colab.*

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shirooo39/DeepCreamPyLab/blob/master/DeepCreamPyLab.ipynb)

A deep learning-based tool to automatically replace censored artwork in hentai with plausible reconstructions.

Before DeepCreamPy can be used, the user must color censored regions in their hentai green with an image editing program like GIMP or Photoshop. DeepCreamPy takes the green colored images as input, and a neural network automatically fills in the censored regions.


<p align="center">
	<img src="https://github.com/deeppomf/DeepCreamPy/blob/master/readme_images/mermaid_collage.png" width="800">
</p>

## Features
- Decensoring images of any size
- Decensoring of ANY shaped censor (e.g. black lines, pink hearts, etc.)
- Decensoring of mosaic decensors
- Limited support for decensoring black and white/monochrome images
- Generate multiple variations of decensors from the same image

## Limitations
The decensorship is for color hentai images that have minor to moderate censorship of the pen-s or vag-na. If a vag-na or pen-s is completely censored out, decensoring will be ineffective.

It does NOT work with:
- Hentai with screentones (e.g. printed hentai)
- Real life porn
- Censorship of nipples
- Censorship of anus
- Animated gifs/videos

Usage:
* [Decensoring tutorial](DCP/docs/USAGE.md)
* [Troubleshooting for installing](DCP/ocs/TROUBLESHOOTING.md)
* [Troubleshooting for poor quality decensors](DCP/docs/TROUBLESHOOTING_DECENSORS.md)

Miscellaneous:
* [FAQ](DCP/docs/FAQ.md)

Special thanks to deeppomf, style00dollar, ccppoo, IAmTheRedSpy, 0xb8, deniszh, Smethan, harjitmoe, itsVale, StartleStars, and SoftArmpit for their contributions!

## License
Source code and official releases/binaries are distributed under the [GNU Affero General Public License v3.0](LICENSE.md).

## Acknowledgements
Example mermaid image by Shurajo & AVALANCHE Game Studio under [CC BY 3.0 License](https://creativecommons.org/licenses/by/3.0/). The example image is modified from the original, which can be found [here](https://opengameart.org/content/mermaid).

Neural network code is modified from Forty-lock's project [PEPSI](https://github.com/Forty-lock/PEPSI), which is the official implementation of the paper [PEPSI : Fast Image Inpainting With Parallel Decoding Network](http://openaccess.thecvf.com/content_CVPR_2019/html/Sagong_PEPSI__Fast_Image_Inpainting_With_Parallel_Decoding_Network_CVPR_2019_paper.html). [PEPSI](https://github.com/Forty-lock/PEPSI) is licensed under the MIT license.

Training data is modified from gwern's project [Danbooru2017: A Large-Scale Crowdsourced and Tagged Anime Illustration Dataset](https://www.gwern.net/Danbooru2017) and other sources.

See [ACKNOWLEDGEMENTS.md](DCP/docs/ACKNOWLEDGEMENTS.md) for full license text of these projects.
