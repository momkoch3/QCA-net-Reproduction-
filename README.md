# QCA-net-Reproduction-
This repository contains all the files used to reproduce Figure 3 from the paper:  3D convolutional neural networks-based segmentation to acquire quantitative criteria of the nucleus during mouse embryogenesis (https://www.nature.com/articles/s41540-020-00152-8)

The Training notebook files themselves contain all the necessary pre-processing steps and the architecture of a single network. The training loop can also be found in these files.
The testing notebooks contain code to test the scores of the trained networks and contain e.g. loss curves and IoU scores. The post-processing_Watershed_Image_plot file contains the post-processing process which includes re-interpolation and application of the watershed algorithm.

We also wanted to upload the trained networks, but alas these files were too big to upload.

Please also read our blog post, which explains all the steps we took to reproduce the results:
https://hackmd.io/5yhN0bTqSza-951Vd-_NLA?view
