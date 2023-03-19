### SI3DP++ project page

B. S. Shim, J. H. Choe and J. -U. Hou, "Source Identification of 3D Printer Based on Layered Texture Encoders," in IEEE Transactions on Multimedia, doi: 10.1109/TMM.2022.3233764.


Dataset will be available after publication.
Please refer our previous work [SI3DP](https://github.com/juhou/SI3DP)


![SI3DP](https://github.com/juhou/SI3DPpp/blob/main/figure_overall.PNG)


### Abstract

With the rapid growth in the 3D printing content market, various unprecedented criminal cases and copyright protection issues are emerging. In response to this imminent and emergent difficulty, we propose a forensic technique for identifying the source of 3D printed products based only on the surface image with no additional tools. This is used to develop database and benchmarks to be used for tracing and finding the sources and origins of 3D printing objects. In fact, the surface texture of 3D printed objects presents, inevitably, very fine periodic traces owing to hardware characteristics during the manufacturing process. We systematically analyzed the causes and factors related to these fine features, and propose a technology using them as unique fingerprints for specific 3D printed objects. As benchmarks, we obtained microscopic close-up images and full-object images from 464 printed objects from 29 different printing options. A certain level of performance was achieved using six benchmarks including printer, and device-level identification. We improved the classification performance to an accuracy of 95\% by using additional inspection information. Moreover, we extended the baseline study based on the benchmark set to forensic test scenarios from multiple perspectives in preparation for real situations. Finally, we deformed 3D printed objects and applied our approach to validate post-processing situations to avoid source identification. We reveal both the dataset and detailed experimental design to provide an opportunity to facilitate future in-depth research related to forensics and protection of intellectual property. 


## Setup

- Python 3.7.0 ~ 3.7.9
- CUDA Version 11.0

1. Nvidia driver, CUDA toolkit 11.0, install Anaconda.

2. Install pytorch 
        
        conda install pytorch torchvision cudatoolkit=11.0 -c pytorch

3. Install various necessary packages in requirements.txt

        pip install -r requirements.txt

## Dataset

![Dataset](./assets/motivation.PNG)
