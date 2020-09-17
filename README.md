
# *<center>Flickr1024: A Large-Scale Dataset for Stereo Image Super-Resolution</center>* 

***<center><a href="https://yingqianwang.github.io/homepage" target="_blank">Yingqian Wang</a>&emsp; Longguang Wang&emsp; Jungang Yang&emsp; Wei An&emsp; <a href="http://yulanguo.me/" target="_blank">Yulan Guo</a></center>*** <br>

### <center><img src="https://raw.github.com/YingqianWang/Flickr1024/master/pics/Flickr1024.jpg" width="480"></center>

### *Flickr1024 is a large-scale stereo image dataset which consists of 1024 high-quality image pairs and covers diverse senarios. Details of this dataset can be found in our published paper* [<a href="http://openaccess.thecvf.com/content_ICCVW_2019/papers/LCI/Wang_Flickr1024_A_Large-Scale_Dataset_for_Stereo_Image_Super-Resolution_ICCVW_2019_paper.pdf">PDF</a>]. *Although the Flickr1024 dataset was originally developed for Stereo Image Super-Resolution (Click [here](https://github.com/YingqianWang/Awesome-Stereo-Image-SR) for an overview), it has also been used for many other tasks such as reference-based SR, stereo matching, stereo image denoising, etc. See [Related Work](## Related Work) for details.*<br>

## Sample Images

<br><img src="https://raw.github.com/YingqianWang/Flickr1024/master/pics/Sample Images.jpg"><br><br>

## Downloads
* The ***Flickr1024*** dataset can be downloaded via
***<a href="https://pan.baidu.com/s/1YD76gpQ2WjkhjkMnHmU3tQ" target="_blank">Baidu Drive</a>*** or 
***<a href="https://drive.google.com/drive/folders/10LTXCSp9UqY9A9HVj3sAf7zmS4KdJo2T?usp=sharing" target="_blank">Google Drive</a>***

## Notations
* The ***Flickr1024*** dataset is available for ***non-commercial*** use only. 
  Therefore, You agree **NOT** to reproduce, duplicate, copy, sell, trade, or resell any portion of the images and any portion of derived data.
* All images on the ***Flickr1024*** dataset are obtained from ***<a href="https://flickr.com" target="_blank">Flickr</a>***
and they are not the property of our laboratory. 
* We reserve the right to terminate your access to the ***Flickr1024*** dataset at any time.

## Acknowledgement
We would like to thank ***<a href="https://www.flickr.com/photos/stereotron/" target="_blank">Sascha Becher</a>***
 and ***<a href="https://www.flickr.com/photos/tombentz" target="_blank">Tom Bentz</a>*** for the approval of using their cross-eye stereo photographs.

## Citiations
```
  @InProceedings{Flickr1024,
  author    = {Wang, Yingqian and Wang, Longguang and Yang, Jungang and An, Wei and Guo, Yulan},
  title     = {Flickr1024: A Large-Scale Dataset for Stereo Image Super-Resolution},
  booktitle = {International Conference on Computer Vision Workshops},
  pages     = {3852-3857},
  month     = {Oct},
  year      = {2019}
  }
  
  @Article{PAM,
  author  = {Wang, Longguang and Guo, Yulan and Wang, Yingqian and Liang, Zhengfa and Lin, Zaiping and Yang, Jungang and An, Wei},
  title   = {Parallax Attention for Unsupervised Stereo Correspondence Learning},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year    = {2020},
  }
  
  @inproceedings{PASSRnet,
  title     = {Learning parallax attention for stereo image super-resolution},
  author    = {Wang, Longguang and Wang, Yingqian and Liang, Zhengfa and Lin, Zaiping and Yang, Jungang and An, Wei and Guo, Yulan},
  booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages     = {12250--12259},
  year      = {2019}
  }
```

## Related Work
The ***Flickr1024*** dataset was used by the following works for different tasks:

#### Stereo Image Super-Resolution:
* Parallax Attention for Unsupervised Stereo Correspondence Learning, *TPAMI 2020*, **[<a href="https://github.com/LongguangWang/PAM" target="_blank">code</a>]**.
* Learning Parallax Attention for Stereo Image Super-resolution, *CVPR 2019*. **[<a href="https://arxiv.org/pdf/1903.05784.pdf" target="_blank">pdf</a>]**, **[<a href="https://github.com/LongguangWang/PASSRnet" target="_blank">code</a>]**.
* A Stereo Attention Module for Stereo Image Super-Resolution, *IEEE Signal Processing Letters 2020*. **[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8998204" target="_blank">pdf</a>]**, **[<a href="https://github.com/XinyiYing/SAM" target="_blank">code</a>]**.
* Non-Local Nested Residual Attention Network for Stereo Image Super-Resolution, *ICASSP 2020*, **[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9054687" target="_blank">pdf</a>]**.
* Stereoscopic Image Super-Resolution with Stereo Consistent Feature, *AAAI 2020*. **[<a href="https://www.aaai.org/Papers/AAAI/2020GB/AAAI-SongW.10348.pdf" target="_blank">pdf</a>]**.
* Parallax-based Spatial and Channel Attention for Stereo Image Super-resolution, *IEEE Access 2019*. **[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8936066" target="_blank">pdf</a>]**.

#### Stereo Image Denoising:
* Self-Convolution: A Highly-Efficient Operator for Non-Local Image Restoration, *arXiv 2020*, **[<a href="https://arxiv.org/pdf/2006.13714.pdf" target="_blank">pdf</a>]**.

#### Reference-based Image Super-Resolution:
* Feature Representation Matters: End-to-End Learning for Reference-based Image Super-resolution, *ECCV 2020*, **[<a href="http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490222.pdf" target="_blank">pdf</a>]**.

#### Stereo Matching:
* Learning Stereo from Single Images, *ECCV 2020*, **[<a href="https://arxiv.org/pdf/2008.01484.pdf" target="_blank">pdf</a>]**.

#### Other Tasks:
* Mononizing Binocular Videos, *ACM Transactions on Graphics 2020*, **[<a href="https://arxiv.org/pdf/2009.01424.pdf" target="_blank">pdf</a>]**.
* Convolutional Neural Networks: A Binocular Vision Perspective, *arXiv 2019*. **[<a href="https://arxiv.xilesou.top/pdf/1912.10201.pdf" target="_blank">pdf</a>]**.
* Holopix50k: A Large-Scale In-the-wild Stereo Image Dataset, *arXiv 2020*, **[<a href="https://arxiv.org/pdf/2003.11172.pdf" target="_blank">pdf</a>]**.

## Other Stereo Image Datasets
* ***<a href="http://www.cvlibs.net/datasets/kitti/index.php" target="_blank">The KITTI Vision Benchmark Suite</a>***
* ***<a href="http://vision.middlebury.edu/stereo/" target="_blank">The Middlebury Stereo Vision Page</a>***
* ***<a href="https://www.eth3d.net/" target="_blank">The ETH3D Benchmark</a>***
* ***<a href="https://github.com/YuhuaXu/StereoDataset" target="_blank">The InStereo2K Dataset</a>***
* ***<a href="http://github.com/leiainc/holopix50k" target="_blank">The Holopix50k Dataset</a>***
* ***<a href="https://sites.google.com/view/wsvd/" target="_blank">The WSVD Dataset</a>***

## Contact
Any question regarding this work can be addressed to ***wangyingqian16@nudt.edu.cn***.

