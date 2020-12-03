# Source code for STAC: [A Simple Semi-Supervised Learning Framework for Object Detection](https://arxiv.org/pdf/2005.04757.pdf)

My notes:

1. I do not think you can train and get reasonable results using `1 gpu`. Since the batch size per GPU is only 1. Too small total batch_size will make network hard to converge.
2. Each GPU needs to have 16 RAM.  We train on 8 V100 and it takes around 8-10 hours.
