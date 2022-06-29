<div align="center">
<h1> MiV Spike Classification </h1>

[![MiV-OS][badge-miv-os]][link-mivos-repo]

</div>

## Tag

Classification, Machine Learning, Supervised Learning, Automation

## Topic Description

The quality of automatic channel masking can be improved if we can directly classify the spike cutout shape. Classifying neuronal spike signal is visually intuitive, but we want better machinary to include as part of `MiV-OS` automatic channel masking. The feature should be able to classify whether the cutout signal is neuronal spike, no-spike, or other unknwon spike.

Start with the dataset provided in `MiV-OS` optogenetic sample. If desire, we can provide more readout data for training/test.

## Useful Resources

Here are some links for building a simple classifier. 

- https://www.tensorflow.org/tutorials/keras/regression
- https://scikit-learn.org/stable/tutorial/basic/tutorial.html
- https://github.com/skim0119/DeepLearning_Note
 
### References/Related Literatures

Below are papers using these methods to do spike classification.

- https://iopscience.iop.org/article/10.1088/1741-2552/abc8d4
- https://iopscience.iop.org/article/10.1088/1741-2552/ab4896

## Instruction

Feel free to contact if you have any question, and feel free to report directly with any results. If you make progress in the work, we will request you to properly implement the method with _test_ and _documentations_. (Check [contributing guide](https://github.com/GazzolaLab/MiV-OS/blob/main/CONTRIBUTING.md))

<!-- hyperlinks -->
 
[badge-miv-os]: https://img.shields.io/badge/-MindInVitro--OS-fa8546?style=flat
[link-mivos-repo]: https://github.com/GazzolaLab/MiV-OS
