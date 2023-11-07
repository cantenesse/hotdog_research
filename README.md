# hotdog_research

This contains a research notebook called `seefood.ipynb`. It contains the data wrangling, training, testing, model building, and validation for a hotdog picture classifier. It uses tensorflow to build a neural network and uses an off-the-shelf CNN called `Inception-ResNet-v2` where weights are initiated with `ImageNet`. The dataset resides within this project and the training process is contained within the notebook.

The execution of the cells in this notebook will build a model and export it to a file. I've loaded the model in S3 and it is used in (hotdog_api|https://github.com/cantenesse/hotdog_api) where it's loaded and `predict()` is called.
