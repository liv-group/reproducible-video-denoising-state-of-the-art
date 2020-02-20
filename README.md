# reproducible-video-denoising-state-of-the-art
Collection of popular and reproducible video denoising works.

Criteria: works must have codes available, and the reproducible results which demonstrate promising or state-of-the-art performances for video denoising.

This format of the collection is similar to [reproducible-image-denoising](https://github.com/wenbihan/reproducible-image-denoising-state-of-the-art)

Note: The first part of this repo includes Gaussian noise removal, and later will include more works for handling other noise distribution or real noise.
Note: We are working on addding more methods to the list. Please feel free to contribute to this repo.

## Video Denoising Algorithms (Gaussian)

#### Local Filtering


#### Non-Local Methods

 * VBM3D [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Matlab]](http://www.cs.tut.fi/~foi/GCF-BM3D/bm3d_matlab_package_3.0.5.zip) [[Python]](http://www.cs.tut.fi/~foi/GCF-BM3D/bm3d_python_package_3.0.6.tar.gz) [[PDF]](http://www.cs.tut.fi/~foi/GCF-BM3D/VBM3D_EUSIPCO_2007.pdf)
   * Video denoising by sparse 3D transform-domain collaborative filtering (EUSIPCO 2007), Dabov et al.
 * VBM4D [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Code]](http://www.cs.tut.fi/~foi/GCF-BM3D/VBM4D_v1.zip) [[PDF]](http://www.cs.tut.fi/~foi/papers/VBM4D-TIP-2cols.pdf)
   * Video Denoising, Deblocking and Enhancement Through Separable 4-D Nonlocal Spatiotemporal Transforms (TIP 2012), Maggioni et al.
 * SALT [[Web]](http://transformlearning.csl.illinois.edu/) [[Code]](hhttps://github.com/wenbihan/salt_iccv2017) [[PDF]](http://transformlearning.csl.illinois.edu/assets/Bihan/ConferencePapers/BihanICCV2017salt.pdf)
   * Joint Adaptive Sparsity and Low-Rankness on the Fly: An Online Tensor Reconstruction Scheme for Video Denoising (ICCV 2017), Wen et al.
   
#### Bayesian Approach

 * VNLB [[Web]](https://github.com/pariasm/vnlb) [[Code]](https://github.com/pariasm/vnlb) [[PDF]](https://link.springer.com/article/10.1007/s10851-017-0742-4)
   * Video Denoising via Empirical Bayesian Estimation of Space-Time Patches (JMIV 2017), Arias and Morel

#### Deep Learning

 * FastDVDnet [[Web]](https://github.com/hsijiaxidian/FOCNet) [[Code]](https://github.com/m-tassano/fastdvdnet) [[PDF]](https://arxiv.org/pdf/1907.01361v1.pdf)
   * FOCNet: A Fractional Optimal Control Network for Image Denoising (CVPR 2019), Jia et al.