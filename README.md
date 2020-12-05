# Semantic Segmentation of Brain Abnormalities

In this notebook I will implement a Semantic Segmentation task on a dataset including MR Images of the brain to detect brain abnormalities.

The dataset I will be using contains brain MR images together with manual FLAIR abnormality segmentation masks obtained from The Cancer Imaging Archive (TCIA).
Images correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available. (Data source: [The Cancer Imagin Archrive](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LGG#6abaca285cee4c9cac59b0bcff944658))

## Sample Images

MR Image of Brain------------------------------Segmentation Mask 

![img](https://drive.google.com/uc?export=view&id=1_Mf8c34ZVBq4nnj4cskZzSKjRk8hm3Cf)
![msk](https://drive.google.com/uc?export=view&id=1ureQ16A5hlGbEc3-inWU4nnp2xrdg8Cg)

## Dependencies
- os
- numpy
- random 
- datetime
- matplotlib
- tqdm
- tensorflow 
    - layers
    - models
- PIL 
    - Image
- skimage
    - transform
    - io
- cv2

## Sample Results

MR Image-----------------------Ground Truth Mask--------------Predicted Mask 


![img1](https://drive.google.com/uc?export=view&id=139Vx_MKuwRiWz7Xx6vniBhOYFFe7xp4y)
![img2](https://drive.google.com/uc?export=view&id=18Xk2JAI3EXlRhxJqTuQbzFnn_wZp3bXu)
![img3](https://drive.google.com/uc?export=view&id=1RJ_Y7tGeKSu8IHRjxJq3-7K1LWhr-VOJ)


## Contact
If you want to contact me you can reach me at [kasra.azizbaigi@gmail.com](mailto:kasra.azizbaigi@gmail.com)

## License
This project uses the following license: [GNU General Public License v3.0](https://github.com/KasraAz75/LRUCache/blob/main/LICENSE).
