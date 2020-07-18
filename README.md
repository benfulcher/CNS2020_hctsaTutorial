# _hctsa_ Tutorial (CNS 2020)

This site will hold details and resources for the 3-hour tutorial on _hctsa_ for the online Computational Neuroscience Society (CNS) Conference, 2020.

PDF of the tutorial main slides are [here](https://doi.org/10.6084/m9.figshare.12671900.v1).

Information about the tutorial is [here](https://www.cnsorg.org/cns-2020-tutorials#T7).

### Description

Massive open datasets of neural dynamics, from microscale neuronal circuits to macroscale population-level recordings, are becoming increasingly available to the computational neuroscience community.
There are myriad ways to quantify different types of structure in the univariate dynamics of any individual component of a neural system, including methods from statistical time-series modeling, the physical nonlinear time-series analysis literature, and methods derived from information theory.
Across this interdisciplinary literature of thousands of time-series analysis methods, each method gives unique information about the measured dynamics.
However, the choice of analysis methods in any given study is typically subjective, leaving open the possibility that alternative methods might yield better understanding or performance for a given task.

In this tutorial, I will introduce highly comparative time-series analysis, implemented as the software package hctsa, which partially automates the selection of useful time-series analysis methods from an interdisciplinary library of over 7000 time-series features.
I will demonstrate how _hctsa_ can be used to extract useful information from various neural time-series datasets.
We will work through a range of applications using fMRI (mouse and human) and EEG (human) time-series datasets, including how to:
1. determine the relationship between structural connectivity and fMRI dynamics in mouse and human;
2. understand the effects of targeted brain stimulation using DREADDs using mouse fMRI; and
3. classify seizure dynamics and extract sleep-stage information from EEG.

I will walk you through an analysis of a 5-class problem involving EEG data, following [this tutorial](https://github.com/benfulcher/hctsaTutorial_BonnEEG).

I will be answering questions via the [neurostars forum](https://neurostars.org/t/cns-2020-tutorial-t7-characterizing-neural-dynamics-using-highly-comparative-time-series-analysis/9597).

### Software tools

If you want to play along with the 5-class problem at home, you can read the readme and install the [_hctsa_ software package](https://github.com/benfulcher/hctsa) (Matlab).
_hctsa_ documentation is available [here](https://hctsa-users.gitbook.io/hctsa-manual/).

### Background reading

1. B.D. Fulcher, N. S. Jones. hctsa: A computational framework for automated time-series phenotyping using massive feature extraction. Cell Systems 5(5): 527 (2017). [Link](https://doi.org/10.1016/j.cels.2017.10.001).
2. B.D. Fulcher, M.A. Little, N.S. Jones. Highly comparative time-series analysis: the empirical structure of time series and their methods. J. Roy. Soc. Interface 10, 20130048 (2013). [Link](https://doi.org/10.1098/rsif.2013.0048).
