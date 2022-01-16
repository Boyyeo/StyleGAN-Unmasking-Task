# StyleGAN-Unmasking-Task
Trying to use pSp Encoder and e4e encoder to deal with unmasking task.
[Paper](https://drive.google.com/file/d/1hECc49hFsTVQfZwZ1sCX3cW8zvYZFS-K/view?usp=sharing) &
[Powerpoint](https://docs.google.com/presentation/d/10xsvNliIboS3RShdMURjmdhW6ZfXcjC-/edit?usp=sharing&ouid=111174497193861703854&rtpof=true&sd=true)
### Usage
1. Real_time_openCV.ipynb is used to do face recognition with pretrained AAFD_e4e model
2. Validation folder is used to validate the trained model
3. Dataset folder is the code used to crawl the celebA_asia dataset and preprocessing by MaskTheFace pipeline 

### Pretrained Model
pretrained model is available to [Download](https://drive.google.com/drive/folders/11LI8eu88XXDJMBXhawxknfxQfa5x09IG?usp=sharing)

### Dataset
Masked dataset is preprocessed with [MaskTheFace pipline](https://github.com/aqeelanwar/MaskTheFace)
1. [FFHQ dataset](https://github.com/NVlabs/ffhq-dataset)
2. [celebA dataset](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
3. [AAFD dataset](https://github.com/JingchunCheng/All-Age-Faces-Dataset)
4. [celebA_asia dataset](https://drive.google.com/drive/folders/1NYPpWiEJAwNP7Map7bW905JKzq7gU9aO?usp=sharing)


### Result training with FFHQ dataset
![e4e and psp result](images/result.jpg?raw=true)

### Result training with AAFD dataset
![e4e and psp result](images/AAFD.jpg?raw=true)

### Result training with celebA_asia dataset (failure case due to low resolution of dataset)
![e4e and psp result](images/celebA_asia.jpg?raw=true)




##  Citation
```
@InProceedings{richardson2021encoding,
      author = {Richardson, Elad and Alaluf, Yuval and Patashnik, Or and Nitzan, Yotam and Azar, Yaniv and Shapiro, Stav and Cohen-Or, Daniel},
      title = {Encoding in Style: a StyleGAN Encoder for Image-to-Image Translation},
      booktitle = {IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
      month = {June},
      year = {2021}
}

@article{tov2021designing,
  title={Designing an Encoder for StyleGAN Image Manipulation},
  author={Tov, Omer and Alaluf, Yuval and Nitzan, Yotam and Patashnik, Or and Cohen-Or, Daniel},
  journal={arXiv preprint arXiv:2102.02766},
  year={2021}
}
```
