# 3D_Full_Body_Reconstruction

This is a course project in GRAP E4005 Computer Graphics in Engineering.

A general procedure is:

1) Used Structure-from-Motion (SfM) and Multi-View Stereo (MVS) to reconstruct 3D human body based on VisualSfM and Meshlab;
2) Employed Feature-Steered Graph Convolutions to classify human body based on Tensorflow Graphics;
3) Tested the classification performance under different scales and summarized existing limitations.

The data are collected by two ways:

1) Online .obj resources
2) Photos taken by the author

The major algorithm is based on Tensorflow Graphics - Semantic Mesh Segmentation: https://github.com/tensorflow/graphics
