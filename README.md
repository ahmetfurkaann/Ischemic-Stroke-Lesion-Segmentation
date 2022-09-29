# Analysis of the Effects of Segmentation Networks and Loss Functions in Ischemic Stroke Lesion Segmentation

Stroke was the cause of one out of every six deaths from cerebrovascular disease in 2020. A stroke occurs in the United States (US)
every 40 seconds. Every 3.5 minutes, people die of a stroke. More than total 795,000 stroke cases occur yearly in the US. This study
aims to detect the ischemic stroke lesion that occurs in the brain. The Ischemic Stroke Lesion Segmentation (ISLES) 2017 data set,
which includes 82 Magnetic Resonance images of 43 patients, was used. The UNet, Attention UNet, Residual UNet, Attention Residual
UNet, and Residual UNet++ segmentation networks were tested. Moreover, Cross Entropy, Dice, IoU, Tversky, Focal Tversky, and
their compound forms were analyzed. The IoU loss function tested on Attention UNet achieved the best performance with the dice score
of 0.766, the IoU score of 0.621, the sensitivity of 0.730, the specificity of 0.997, the precision of 0.805, and the accuracy of 0.993.
