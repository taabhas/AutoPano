# Panorama Stitching

This project implements panorama stitching two or more images in order to create one seamless panorama image. Each image should have few repeated local features (∼30-50% or more, empirically chosen).

### Approach

The classical method follows the illustrated algorithm:

<p align="center">
  <img src="Assets\panoalgo.png" alt="euroc_mh_01_easy" width="500"/>
</p>

The code is provided in Wrapper.ipynb for the input images provided in Set1 Folder.

### Results

The input images are:

<p align="center">
  <img src="Set1\1.jpg" alt="1" width="200"/>
  <img src="Set1\2.jpg" alt="2" width="200"/>
  <img src="Set1\3.jpg" alt="3" width="200"/>
</p>

The resulting stitched Panorama is:
<p align="center">
  <img src="Assets\pano_result.png" alt="euroc_mh_01_easy" width="500"/>
</p>


### Reference
1. https://rbe549.github.io/spring2023/proj/p1/
