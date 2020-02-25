# reproducible-video-denoising-state-of-the-art
Collection of popular and reproducible video denoising works.

Criteria: works must have codes available, and the reproducible results which demonstrate promising or state-of-the-art performances for video denoising.

This format of the collection is similar to [reproducible-image-denoising](https://github.com/wenbihan/reproducible-image-denoising-state-of-the-art)

Please feel free to contribute to this repo.

## Video Denoising Algorithms

#### Online Methods

 * ReLD [[Web]](https://www.ece.iastate.edu/~hanguo/denoise.html) [[Code]](https://www.ece.iastate.edu/~hanguo/ReLD_Denoising.zip) [[PDF]](https://www.ece.iastate.edu/~namrata/VideoDenoising_SSP16.pdf)
   * Video denoising via online sparse and lowrank matrix decomposition (SSP 2016), Guo and Vaswani.
 * VIDOSAT [[Web]](https://github.com/wenbihan/vidosat_icip2015) [[Code]](https://github.com/wenbihan/vidosat_icip2015) [[PDF]](https://arxiv.org/pdf/1710.00947.pdf)
   * VIDOSAT - High-dimensional Sparsifying Transform Learning for Online Video Restoration (TIP 2019), Wen et al.

#### Non-Local Methods

 * VBM3D [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Matlab]](http://www.cs.tut.fi/~foi/GCF-BM3D/bm3d_matlab_package_3.0.5.zip) [[Python]](http://www.cs.tut.fi/~foi/GCF-BM3D/bm3d_python_package_3.0.6.tar.gz) [[PDF]](http://www.cs.tut.fi/~foi/GCF-BM3D/VBM3D_EUSIPCO_2007.pdf)
   * Video denoising by sparse 3D transform-domain collaborative filtering (EUSIPCO 2007), Dabov et al.
 * VBM4D [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Code]](http://www.cs.tut.fi/~foi/GCF-BM3D/VBM4D_v1.zip) [[PDF]](http://www.cs.tut.fi/~foi/papers/VBM4D-TIP-2cols.pdf)
   * Video Denoising, Deblocking and Enhancement Through Separable 4-D Nonlocal Spatiotemporal Transforms (TIP 2012), Maggioni et al.  
 * RNLF [[Web]](http://iop.math.u-bordeaux.fr/?cat=27) [[Code]](https://github.com/csutour/RNLF) [[PDF]](https://hal.archives-ouvertes.fr/hal-00854830v3/document)
   * Adaptive regularization of the NL-means: Application to image and video denoising (TIP 2014), Sutour et al.  
 * SALT [[Web]](http://transformlearning.csl.illinois.edu/) [[Code]](https://github.com/wenbihan/salt_iccv2017) [[PDF]](http://transformlearning.csl.illinois.edu/assets/Bihan/ConferencePapers/BihanICCV2017salt.pdf)
   * Joint Adaptive Sparsity and Low-Rankness on the Fly: An Online Tensor Reconstruction Scheme for Video Denoising (ICCV 2017), Wen et al.
   
#### Bayesian Approach

 * VNLB [[Web]](https://github.com/pariasm/vnlb) [[Code]](https://github.com/pariasm/vnlb) [[PDF]](https://link.springer.com/article/10.1007/s10851-017-0742-4)
   * Video Denoising via Empirical Bayesian Estimation of Space-Time Patches (JMIV 2017), Arias and Morel

#### Deep Learning

 * VNLNet [[Web]](https://github.com/axeldavy/vnlnet) [[Code]](https://github.com/axeldavy/vnlnet) [[PDF]](https://arxiv.org/pdf/1811.12758.pdf)
   * Non-Local Video Denoising by CNN (Arxiv 2018), Davy et al.
 * FastDVDnet [[Web]](https://github.com/hsijiaxidian/FOCNet) [[Code]](https://github.com/m-tassano/fastdvdnet) [[PDF]](https://arxiv.org/pdf/1907.01361.pdf)
   * FastDVDnet: Towards Real-Time Video Denoising Without Explicit Motion Estimation (Arxiv 2019), Tassano et al.

#### Model-blind Learning

 * BlindDenoising [[Web]](https://github.com/tehret/blind-denoising) [[Code]](https://github.com/tehret/blind-denoising) [[PDF]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ehret_Model-Blind_Video_Denoising_via_Frame-To-Frame_Training_CVPR_2019_paper.pdf)
   * Model-Blind Video Denoising via Frame-To-Frame Training (CVPR 2019), Tassano et al. 
 * ViDeNN [[Web]](https://github.com/clausmichele/ViDeNN) [[Code]](https://github.com/clausmichele/ViDeNN) [[PDF]](http://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Claus_ViDeNN_Deep_Blind_Video_Denoising_CVPRW_2019_paper.pdf)
   * ViDeNN: Deep Blind Video Denoising (CVPRW 2019), Claus and Gemert 