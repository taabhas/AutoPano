# Panorama Stitching

This project implements panorama stitching two or more images in order to create one seamless panorama image. Each image should have few repeated local features (∼30-50% or more, empirically chosen).

### Approach

The classical method follows the illustrated algorithm:

<p align="center">
  <img src="Assets\panoalgo.png" alt="euroc_mh_01_easy" width="500"/>
</p>

The code is provided in Wrapper.ipynb for the input images provided in Set1 Folder.

### Results
#### Set 1
The input images are:

<p align="center">
  <img src="InputData\Set2\1.jpg" alt="1" width="200"/>
  <img src="InputData\Set2\2.jpg" alt="2" width="200"/>
  <img src="InputData\Set2\3.jpg" alt="3" width="200"/>
</p>

The resulting stitched Panorama is:
<p align="center">
  <img src="OutputResults\Output1.png" alt="euroc_mh_01_easy" width="500"/>
</p>

#### Set 2
The input images are:

<p align="center">
  <img src="InputData\CustomSet\custom1.jpg" alt="1" width="200"/>
  <img src="InputData\CustomSet\custom2.jpg" alt="2" width="200"/>
</p>

The resulting stitched Panorama is:
<p align="center">
  <img src="OutputResults\Output2.png" alt="euroc_mh_01_easy" width="500"/>
</p>


### Reference
1. https://rbe549.github.io/spring2023/proj/p1/
