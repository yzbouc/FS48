
> [**Take good care of your fish: fish re-identification with synchronized multi-view camera system**]()  
> Suzhen Fan1, Chengyang Song2, Haiyang Feng1, Zhibin Yu1,2*

1Key Laboratory of Ocean Observation and Information of Hainan Province,
Sanya Oceanographic Institution, Ocean University of China

2College of Electronic Engineering,Ocean University of China


† corresponding author: yuzhibin@ouc.edu.cn; Project website: https://github.com/yzbouc/FS48

This repository contains the official implementation and dataset of the paper "Take good care of your fish: fish re-identification with synchronized multi-view camera system" 
https://www.frontiersin.org/journals/marine-science/articles/10.3389/fmars.2024.1429459/full


> We constructed the first underwater fish re-identification benchmark dataset (FS48) under three camera conditions. FS48 encompasses 48 different fish identities, 10,300 frames, and 39,088 bounding boxes, covering various lighting conditions and background environments.
## Dataset display
> ![Sample1](gt_query/01_C1_seq001_frame0000.jpg)
> ![Sample2](gt_query1/01_C1_seq001_frame0000.jpg)

> 
## Update
- **2024.11.06:** Published by Frontiers in Marine Science.
- **2024.10.8:** The FS48 dataset has been released.

## Get Started

#### Dataset Organization Form
```
|--dataset  
    |--gt_bbox_gallery  
        |--image 1
            :
        |--video n
    |--gt_bbox_train
        |--image 1
            :
    |--gt_query
        |--image 1
            :
    |--gt_query1
        |--image 1
            :
```


## Citation
```
@article{fan2024take,
  title={Take good care of your fish: fish re-identification with synchronized multi-view camera system},
  author={Fan, Suzhen and Song, Chengyang and Feng, Haiyang and Yu, Zhibin},
  journal={Frontiers in Marine Science},
  volume={11},
  pages={1429459},
  year={2024},
  publisher={Frontiers Media SA}
}
```
