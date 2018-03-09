# fastai_deeplearning_v2_pt1
Notes and projects for FastAI's Deep Learning Course Part 1

To run the notebooks in this repository, you must download the data required by each notebook and the Fastai library ([https://github.com/fastai/fastai](https://github.com/fastai/fastai)).

The ideal directory structure will look like the following:

```
    deeplearning_project/
    ├── fastai_deeplearning_v2_pt1/
    │   ├── cnn_experiment_1.ipynb 
    ├── fastai/
    ├── data/
```
where `fastai_deeplearning_v2_pt1` is this repository (which contain deep learning experiments using IPython notebooks), `fastai` is the Fastai library, and `data` contains all the data required to run the analysis in the notebooks. `data` can be a symlink to the drive containing the actual datasets.

You must activate the fastai environment to be able to run the notebooks (follow instructions on the library's Github repository). Also, since the notebooks are in a different folder from the `fastai` library, you'll need to add the library to the system path by executing `import sys; sys.path.append('../fastai/')` at the top of every notebook (you may only need to execute this once). 

The last thing you'll need to download are the pretrained weights of various architectures (e.g. resnext101_64). The pretrained weights can be found here http://files.fast.ai/models/weights.tgz. You need to unzip this file and place it inside the `fastai` folder within the `fastai` repository (yes, there is a subdirectory with the same name as the parent directory).
