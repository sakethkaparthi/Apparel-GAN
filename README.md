# Apparel-GAN
Apparel generation using GAN
# Non conditional GAN
Dataset used: [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)

Optimizer : Adam with LR = 0.0003 for both discriminators and Adam with LR = 0.0001 for generator

Cost function : Mean error (tf.reduce_mean)

# References
[Conditional GAN](https://wiseodd.github.io/techblog/2016/12/24/conditional-gan-tensorflow/)
