# Image_Based_3D_Photo
Based on [CVPR 2020] 3D Photography using Context-aware Layered Depth Inpainting, we present image based 3D photograhpy.
There are four steps to generate 3D vidoe
Input: Single image S
(1) Geerate Depth image D from S
(2) Isolate foregroung mask F and background mask B from D
(3) Generate foreground layer F' and inpaiting background layer B'
(4) Generate images for 3D Video (TGA File)
(5) Used FFMpeg to generated MP4 video file
