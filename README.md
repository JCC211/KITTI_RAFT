# KITTI_RAFT
Using PyTorch and RAFT optical flow to create a video of the first 200 images from the right camera of the KITTI dataset.

This jupyter lab notebook file contains a demo of optical flow using RAFT. The motivation was to practice and learn image tracking and matching using
machine learning.

The contents of this repository are as follows:
- jupyter lab notebook with code and comments for the process

This project was built in a conda virtual environment. All of the libraries and versions in this venv are listed at the end of the jupyter notebook.

This model is likely slower than alternative methods such as SIFT or Harris for feature detection and KNN or KD-trees for matching.
On the contrary, this approach has good accuracy and effiency.
