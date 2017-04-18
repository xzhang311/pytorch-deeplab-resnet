# pytorch-deeplab-resnet
DeepLab resnet model in pytorch

# Usage
The repository contains model definition of deeplab-resnet in pytorch. To use this code, download the deeplab-resnet caffemodel pretrained on VOC into the data folder. After that, run
```
python convert_deeplab_resnet.py
```
to generate the pytorch model file(.pth)

## Acknowledgement
A part of the code has been borrowed from [https://github.com/ry/tensorflow-resnet](https://github.com/ry/tensorflow-resnet)
