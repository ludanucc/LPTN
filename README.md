# Optimize LPTN

### Overview

Optimize LPTN is a fork of LPTN(https://github.com/csjliang/LPTN). This project aims to improve upon the original by changing the number of residual blocks, learning rate, and the optimizer.

Each branch represents a different experiment. 
l1, l2, l3, l4, l6 branches are the experiments that change the number of residual blocks in the low-frequency component.
h1, h2, h4, h5, h6 branches are the experiments that change the number of residual blocks in the high-frequency component.
lr001, lr000001, lr005, lr0005, lr00005 branches are the experiments that change the learning rates for the generator optimizer.
lrd001, lrd000001, lrd005, lrd0005, lrd00005 branches are the experiments that change the learning rates for the discriminator optimizer.

adagrad is the experiment that switches the Adam optimizer to the Adagrad optimizer.
adagrad_l1, adagrad_l2, adagrad_l3, adagrad_l4, adagrad_l6 branches are the experiments that change the number of residual blocks in the low-frequency component with Adagrad optimizer.
adagrad_h1, adagrad_h2, adagrad_h4, adagrad_h5, adagrad_h6 branches are the experiments that change the number of residual blocks in the high-frequency component with Adagrad optimizer.
adagrad_lr001, adagrad_lr000001, adagrad_lr005, adagrad_lr0005, adagrad_lr00005 branches are the experiments that change the learning rates for the generator Adagrad optimizer.
adagrad_lrd001, adagrad_lrd000001, adagrad_lrd005, adagrad_lrd0005, adagrad_lrd00005 branches are the experiments that change the learning rates for the discriminator Adagrad optimizer.

### License

This project is licensed under the Apache 2.0 license, which is the same as the original repository.


### Acknowledgement

Thanks to csjliang(https://github.com/csjliang) for the original project.
