# 3D_Full_Body_Reconstruction

This is a course project in GRAP E4005 Computer Graphics in Engineering.

A general procedure is:

Used Structure-from-Motion (SfM) and Multi-View Stereo (MVS) to reconstruct 3D human body based on VisualSfM and Meshlab;
Employed Feature-Steered Graph Convolutions to classify human body based on Tensorflow Graphics;
Tested the classification performance under different scales and summarized existing limitations.
The data are collected by two ways:

Online .obj resources
Photos taken by the author
The major algorithm is based on Tensorflow Graphics - Semantic Mesh Segmentation: https://github.com/tensorflow/graphics
