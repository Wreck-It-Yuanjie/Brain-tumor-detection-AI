# Brain tumor detection


## About
Welcome to the Brain tumor detection project!

I first estimate a Residual network (ResNet) model to detect whether there exist brain tumors using MRI scans. Compared to the common convolution neural network (CNN) algorithm, ResNet can solve the vanishing gradient problem. I also use transfer learning to reduce the computational time. 

Next, I use ResUNet to localize the tumor in the brain, where pixel level classification is performed.

## Results
* By using ResNet and transfer learning, the brain tumor detection accuracy reaches 98%
* By using ResUNet, we can segment the tumor in the MRI scan image with 95% accuracy
* The model is compiled and deployed using TensorFlow Serving

## Acknowledgement
I would like to thank Udemy course *Modern Artificial Intelligence Masterclass* and the instructor *Dr. Ryan Ahmed*
