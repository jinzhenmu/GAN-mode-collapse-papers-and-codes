# GAN-mode-collapse-papers-and-codes
The problem of mode collapse occurs when the generator network is only able to capture a subset of the variance present in the data distribution. 
整理的关于GAN的模式坍塌与梯度消散文献，全部都是开源的。

[1] Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis 针对CGAN，提出了一种正则化，简单，容易理解

[2] MGAN: Traning  Generative Adversarial Networks with  Multiple Generators  针对模式坍塌问题，最简单粗暴地方式就是增加Generators的数量

[3] MSG-GAN: Multi-Scale Gradients for Generative Adversarial Network--原则上是处理梯度消散的。

【4】Progressive Growing of GANs for Improved Quality, Stability, and Variation

【5】The Numerics of GANs 理论上证明了GAN的不稳定

【6】Stabilizing Training of Generative Adversarial Networks through Regularization 理论上证明了GAN的不稳定

【7】InfoMax-GAN: Improved Adversarial Image Generation via Information Maximization and Contrastive Learning 和互信息有关

【8】Prescribed Generative Adversarial Networks

【9】VEEGAN: Reducing Mode Collapse in GANs using Implicit Variational Learning 模式坍塌的经典论文

【10】 Evolutionary Generative Adversarial Networks 遗传算法加入到GAN里，简单，解决了部分模式坍塌与梯度消散问题

【11】Improved Techniques for Training GANs

【12】Variational Discriminator Bottleneck: Improving Imitation Learning, Inverse RL, and GANs by Constraining Information Flow

【13】 Multi-Agent Diverse Generative Adversarial Networks

【14】 Unrolled Generative Adversarial Networks 对D做了展开操作

【15】 Dual Discriminator Generative Adversarial Nets 双判别器

【16】 Stabilizing GAN Training with Multiple Random Projections 多个D

【17】Comparison of Generative Adversarial Networks Architectures Which Reduce Mode Collapse 对比了PcGAN VEEGAN

【18】REAL OR NOT REAL, THAT IS THE QUESTION   提出RealnessGAN 
