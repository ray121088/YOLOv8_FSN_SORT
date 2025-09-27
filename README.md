# Individual plant detection and tracking for agricultural robotics in precision field management

### Overview
1.	Developed a lightweight, accurate model for individual plant detection and tracking using StrongSORT.
2.	Constructed a labeled dataset covering ten crop and weed species under natural field conditions.
3.	Deployed and validated the model on Jetson Orin NX, demonstrating robust performance in both known and unseen environments.


### Dataset
```
https://drive.google.com/drive/folders/15EeVQGCBORjYmLnFbpup_GIb8GJ6QsfZ?usp=drive_link
```

### Requirements
  Python>=3.7.0
  torch>=1.8.0
  torchvision>=0.9.0

### Reference

```
@software{yolov8_ultralytics,
  author = {Glenn Jocher and Ayush Chaurasia and Jing Qiu},
  title = {Ultralytics YOLOv8},
  version = {8.0.0},
  year = {2023},
  url = {https://github.com/ultralytics/ultralytics},
  orcid = {0000-0001-5950-6979, 0000-0002-7603-6750, 0000-0003-3783-7069},
  license = {AGPL-3.0}
}
@article{du2023strongsort,
  title={Strongsort: Make deepsort great again},
  author={Du, Yunhao and Zhao, Zhicheng and Song, Yang and Zhao, Yanyun and Su, Fei and Gong, Tao and Meng, Hongying},
  journal={IEEE Transactions on Multimedia},
  year={2023},
  publisher={IEEE}
}
```
