# Lite-UNet-A-Lightweight-and-Efficient-Network-for-Cell-Localization
The code of paper: [Lite-UNet: A Lightweight and Efficient Network for Cell Localization](https://www.sciencedirect.com/science/article/pii/S0952197623018183?via%3Dihub)


Refer to [https://github.com/Boom5426/MHFAN/blob/main/Networks/UNet/Lite-UNet.py](https://github.com/Boom5426/MHFAN/blob/main/Networks/UNet/Lite-UNet.py)

## Abstruct:
Cell localization constitutes a fundamental research domain within the realm of pathology image analysis, with its core objective being the precise identification of cell spatial coordinates. The task has always involved the challenge of large color variations among cells, uneven distribution, and overlapping borders. Furthermore, in realistic cell localization scenarios, the existing state-of-the-art methods suffer from high computational costs and slow inference times, which severely reduce the efficiency of computer-assisted. To tackle the above issues, a lightweight and efficient cell localization model named Lite-UNet is proposed. Specifically, the Lite-UNet encompasses three pivotal modules. Firstly, we introduce a gradient aggregation module grounded in difference convolution. This module effectively mitigates the challenge posed by extensive color variations among cells by adeptly leveraging gradient information. Secondly, we propose an efficient plug-and-play graph correlation attention module, which optimizes the feature representation capabilities by encoding higher-order feature associations. Finally, we design a lightweight Ghost\_CBAM module that alleviates the difficulty of uneven cell distribution while forming the base module of the Lite-UNet. Extensive experiments show that our Lite-UNet is capable of locating cells in images quickly and accurately, thus further improving the efficiency of computer-assisted medicine.

## Overview:
![2](https://github.com/Boli-trainee/Lite-UNet/assets/83391363/98ba6c91-267b-4ad3-8059-11b9e2096781)


