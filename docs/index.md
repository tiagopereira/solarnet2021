# SOLARNET 2021 MSSL: Analysis and Interpretation of IRIS data

This page contains instructions and materials for lectures and tutorials given by Tiago Pereira at the SOLARNET school hosted by MSSL in January 2021. There are two ways to work with the materials: download data and necessary packages into your computer (recommended), or online-only using Binder. The Binder option is slower, will timeout when not active, and is meant to be a failsafe option. You can use the Binder version by clicking the link below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tiagopereira/solarnet2021/master?urlpath=tree/notebooks)


## Running on your computer

If you have already followed the python setup for the SOLARNET school, all packages for the lectures and tutorial should already be installed. You can safely ignore the step below to create a new conda environment. The commands below assume you have a conda installation: miniconda ([miniconda](https://conda.io/miniconda.html) or [Anaconda](https://www.anaconda.com/download/)), and have git installed. 

The first step is to clone the repository into a directory of your choice. Open a terminal and navigate to your preferred directory, and then clone the repository:

```bash
git clone https://github.com/tiagopereira/solarnet2021.git solarnet_iris
```

If you don't have git, you can instead [download a zip file](https://codeload.github.com/tiagopereira/solarnet2021/zip/master), but then it will be harder to keep the repository current in case there are updates.


You will end up with a directory called `solarnet_iris`. In the terminal, go to that directory. If have not yet installed the common python packages for the SOLARNET school, you can do it using the provided `environment.yml` (if you have, skip this step):

```bash
conda env create -f environment.yml
```

Then you need to activate the environment:

```bash
conda activate solarnet
```

The last step is to download some data files. Please download the following data files into the directory `solarnet_iris/notebooks`:

* [iris_l2_20180102_153155_3610108077_SJI_1400_t000.fits.gz](http://www.lmsal.com/solarsoft/irisa/data/level2_compressed/2018/01/02/20180102_153155_3610108077/iris_l2_20180102_153155_3610108077_SJI_1400_t000.fits.gz)
* [iris_l2_20140919_051712_3860608353_SJI_2832_t000.fits.gz](http://www.lmsal.com/solarsoft/irisa/data/level2_compressed/2014/09/19/20140919_051712_3860608353/iris_l2_20140919_051712_3860608353_SJI_2832_t000.fits.gz)
* [iris_l2_20180102_153155_3610108077_raster.tar.gz](http://www.lmsal.com/solarsoft/irisa/data/level2_compressed/2018/01/02/20180102_153155_3610108077/iris_l2_20180102_153155_3610108077_raster.tar.gz)
* [aia_20140919_060030_1700_image_lev1.fits](https://drive.google.com/uc?export=download&id=1SgascyixFq7v5LzG2hcxHWJKfe0SssN5)

These downloads are about 350 MB. Once you have them, you are ready to start. From the terminal, in the directory `solarnet_iris/notebooks`, start jupyter:

```bash
jupyter notebook
```

## Slides

Slides from the lectures are not yet available. They will be available later from this page.