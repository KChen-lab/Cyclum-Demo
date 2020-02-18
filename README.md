# Cyclum-Demo:
A self-contained demo of [Cyclum](https://github.com/KChen-lab/Cyclum), in Jupyter notebook, is available in [`mESC.ipynb`](https://github.com/KChen-lab/Cyclum-Demo/blob/master/mESC.ipynb). It works with the mESC dataset ([Computational analysis of cell-to-cell heterogeneity in single-cell RNA-sequencing data reveals hidden subpopulations of cells](https://www.nature.com/articles/nbt.3102)). It shows shows how to start with an expression matrix, then decide the optimal dimensionality, and finally calculate the circular pseudotime. On a computer equipped with an Cuda-ready GPU, it will take about 20 minutes to run. If only CPU is available, it may take around 1 hour.

The analysis of the result was done in R, and a demo is available in [`mesc_analysis.Rmd`](https://kchen-lab.github.io/Cyclum-Demo/mesc_analysis.nb.html). Running it will take around five seconds. The expected result is available in "mesc_analysis.nb.html". It relies on `cyclum-pseudotime.h5`, the result of the Jupyter notebook.

## System requriment:
The code is on Debian GNU/Linux 10 (buster) with both CPU and GPU. The code should run on most mainstream systems (Linux, Mac, Windows) supporting Tensorflow.

## Software dependencies: 

|Software    | Version|
|------------|--------|
|python      | 3.7.4  |
|keras       | 2.2.4  |
|tensorflow  | 1.14.0 |
|numpy       | 1.16.5 |
|pandas      | 0.25.2 |
|scikit-learn| 0.21.3 |
|h5py        | 2.9.0  |
|hdf5        | 1.10.4 |
|jupyter     | 1.0.0  |

We recommend Miniconda to manage the packages. The code should work on packages of newer versions, but in case it fails, you can return to the specific version by, for example, `conda install python=3.7.4`.

## Installation: 
No installation is needed.

## Instructions:
More instructions is availabe through our github repository: https://github.com/KChen-lab/Cyclum.
