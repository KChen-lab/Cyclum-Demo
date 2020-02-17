# Cyclum-Demo:
A self-contained [demo](https://github.com/KChen-lab/Cyclum-Demo/blob/master/mESC.ipynb) of Cyclum, ships with the mESC data.

The demo is available in "mESC.ipynb". It is accessible through jupyter notebook. Instruction for each step is available in the notebook. The expected output is available in "mESC.html". On a computer equipped with an Cuda-ready GPU, it will take about 20 minutes to run. If only CPU is available, it may take around 1 hour.

The analysis of the result was done in R, and a demo is available in "mesc_analysis.Rmd". Running it will take around five seconds. The expected result is available in "mesc_analysis.nb.html".

## System requriment:
Operating System: Debian GNU/Linux 10 (buster)

The code should run on most mainstream systems (Linux, Mac, Windows) supporting Tensorflow. Enabling GPU computing gives significantly better performance (5 minutes vs 30 minutes for CPU), but is not requried.

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
