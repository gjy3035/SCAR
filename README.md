# SCAR
The code for "SCAR: Spatial-/Channel-wise Attention Regression Networks for Crowd Counting"

This is an official implementation of the paper "SCAR: Spatial-/Channel-wise Attention Regression Networks for Crowd Counting" (completed in **September 2018**, accepted by Neurocomputing in **August 2019**).

The original implementation of our paper is similar to this framework: [**GCC-SFCN**](https://github.com/gjy3035/GCC-SFCN). Recently, we re-implement SCAR using [**C^3 Framework**](https://github.com/gjy3035/C-3-Framework) and achieve a better performance than the original implementation. Thus, this repo provide the key code and hyperparameters in C^3 Framework.


## Performance on Shanghai Tech Part B (MAE/MSE)

|          Method       |   MAE   |    MSE   | 
|-----------------------|---------|----------|
| The orginal paper     |   9.5   |   15.2   |
| C^3 Framework         | **9.0** | **13.8** |


## Citing
If you use the code, please cite the following paper:
```
@ARTICLE{wang2019weakly, 
author={Wang, Qi and Gao, Junyu and Li, Xuelong}, 
journal={IEEE Transactions on Image Processing}, 
title={Weakly Supervised Adversarial Domain Adaptation for Semantic Segmentation in Urban Scenes}, 
year={2019}, 
volume={28}, 
number={9}, 
pages={4376-4386}, 
}
```
