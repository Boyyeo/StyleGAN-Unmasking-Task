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




##  Running Code
Main Code Please reference to 
[pSp Encoder](https://github.com/eladrich/pixel2style2pixel) and 
[e4e Encoder](https://github.com/omertov/encoder4editing)
