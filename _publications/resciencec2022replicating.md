---
title: "Replicating and Improving GAN2Shape Through Novel Shape Priors and Training Steps"
excerpt: "Pan et al. [1] propose an unsupervised method named GAN2Shape that purportedly isable to recover 3D information stored in the weights of a pre‐trained StyleGAN2 model, to produce 3D shapes from 2D images. We re‐implement the method proposed by Pan et al. [1] with regards to 3D shape re‐construction, and extend their work. Our extensions include novel prior shapes andtwo new training techniques. While the code‐base relating to GAN2Shape was largely re-written, many external dependencies, which the original authors relied on, had to be imported. We replicate the results of Pan et al. [1] on a subset of the LSUN Cat, LSUN Car [2] and CelebA [3] datasets and observe varying degrees of success. We perform several experiments and illustrate the successes and shortcomings of the method. Our novel shape priors improve the 3D shape recovery in certain cases where the original shape prior was unsuitable. Our generalized training approach shows initial promise, but has to be confirmed with increased computational resources."
date: 2022-05-01
header:
  image: /assets/images/publications/resciencec2022replicating/plotly__im_1.gif
  teaser: /assets/images/publications/resciencec2022replicating/plotly__im_1.gif

---

*Alessio Galatolo and Alfred Nilsson*

**ReScience C Journal (2022)**

----

Pan et al. [^1] propose an unsupervised method named GAN2Shape that purportedly isable to recover 3D information stored in the weights of a pre‐trained StyleGAN2 model, to produce 3D shapes from 2D images. We re‐implement the method proposed by Pan et al. [^1] with regards to 3D shape re‐construction, and extend their work. Our extensions include novel prior shapes andtwo new training techniques. While the code‐base relating to GAN2Shape was largely re-written, many external dependencies, which the original authors relied on, had to be imported. We replicate the results of Pan et al. [1] on a subset of the LSUN Cat, LSUN Car [^2] and CelebA [^3] datasets and observe varying degrees of success. We perform several experiments and illustrate the successes and shortcomings of the method. Our novel shape priors improve the 3D shape recovery in certain cases where the original shape prior was unsuitable. Our generalized training approach shows initial promise, but has to be confirmed with increased computational resources.

[Full text (pdf)](/assets/publications/resciencec2022replicating.pdf){: .btn .btn--primary}
[View article (doi.org)](https://doi.org/10.5281/zenodo.6574685){: .btn .btn--primary}
[Code (github.com)](https://github.com/alessioGalatolo/GAN-2D-to-3D){: .btn .btn--primary}

[^1]: Pan, X., B. Dai, Z. Liu, C. Loy, and P. Luo. "Do 2D GANs Know 3D Shape? Unsupervised 3D Shape Reconstruction from 2D Image GANs." In International Conference on Learning Representations (ICLR) 2021. Vienna, Austria, 2021.
[^2]: Yu, Fisher, Ari Seff, Yinda Zhang, Shuran Song, Thomas Funkhouser, and Jianxiong Xiao. "Lsun: Construction of a large-scale image dataset using deep learning with humans in the loop." arXiv preprint arXiv:1506.03365 (2015).
[^3]: Liu, Ziwei, Ping Luo, Xiaogang Wang, and Xiaoou Tang. "Deep learning face attributes in the wild." In Proceedings of the IEEE international conference on computer vision, pp. 3730-3738. 2015.
