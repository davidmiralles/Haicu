# Haptic Curvatures (Haicu) :open_file_folder:
In this repository is available a virtual haptic information dataset, generated from typycal household objects. This information is based in local curvatures of the virtual objects and captured by the simulation of 3 fingers aproaching to the 3D figures.

<img src="https://user-images.githubusercontent.com/66378073/142606662-5f03dd82-e4a6-4a6d-9dc7-dc3cc6c2fc36.png" alt="Fingers simulation" width="300" height="auto">
<img src="https://user-images.githubusercontent.com/66378073/142606413-bcf065c3-3cc1-4574-b288-e50a9ec9f819.png" alt="Curvature capture" width="500" height="auto">

## Capture system

## Stimuli
The objects used as stimuli of this dataset have been drawn from [ShapeNet](https://shapenet.org), an online 3D figures dataset. Specifically, we use 10 different figures: a bowl, a camera, a paper clip, a fork, a hammer, a computer mouse, a pair of scissors, a spoon, a wristwatch and a bottle of wine.

<img src="https://user-images.githubusercontent.com/66378073/142599364-10df7d6e-0bc6-482b-bb72-0ae3cd042702.png" alt="ShapeNet figrues" width="600" height="auto">

## Format of the dataset

The dataset is contained in the folder `shapenet_data/` and distributed in a *txt* file per figure, named as the corresponding object (e.g. `bowl.txt`). Each *txt* file contains 21000 lines, where each line is a sample formed by the 3 floats of time (e.g. ``0 0.01 0.109``).

## References

Angel  X.  Chang,  Thomas  Funkhouser,  Leonidas  Guibas,  Pat  Hanrahan,Qixing  Huang,  Zimo  Li,  Silvio  Savarese,  Manolis  Savva,  Shuran  Song,Hao Su, Jianxiong Xiao, Li Yi, and Fisher Yu. ShapeNet: An Information-Rich 3D Model Repository. Technical Report arXiv:1512.03012 [cs.GR],Stanford  University  —  Princeton  University  —  Toyota  TechnologicalInstitute at Chicago, 2015.
