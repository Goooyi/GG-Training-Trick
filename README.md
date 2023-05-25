# GG-Training-Trick

## General Trianing

## Training AI models at a large scale

[GETTING STARTED WITH FULLY SHARDED DATA PARALLEL(FSDP)](https://pytorch.org/tutorials/intermediate/FSDP_tutorial.html#getting-started-with-fully-sharded-data-parallel-fsdp)

## Bottleneck Issue

[About training bottleneck](https://discuss.pytorch.org/t/how-to-prefetch-data-when-processing-with-gpu/548/19)

[A reddit post about bottleneck](https://www.reddit.com/r/MachineLearning/comments/qr0rck/d_how_to_avoid_cpu_bottlenecking_in_pytorch/)

[Efficient PyTorch I/O library for Large Datasets, Many Files, Many GPUs](https://pytorch.org/blog/efficient-pytorch-io-library-for-large-datasets-many-files-many-gpus/)

[Write Custome Stream Dataloader when the Dataset is too big to fit in memeory](https://jamesmccaffrey.wordpress.com/2021/03/08/working-with-huge-training-data-files-for-pytorch/): Or sometimes just recreate new Dataset object that contains only part of the whole dataset during training, this way may need to take care of the sharding of the dataset, but you may also just skip it, duplicated sample may stabilize the training process 

Batched data augmentations using [Kornia](https://github.com/kornia/kornia) since pytorch doesn't support it yet.

[PyTorch 效能懶人包](https://hackmd.io/@-CDCNK_qTUicXsissQsHMA/SJ6Gjpxv8)
