# MVTec AD-C Robustness Benchmark: The Corrupted MVTec Anomaly Detection Dataset

![MVTec AD-C](https://github.com/YurongChen1998/MVTec-AD-C/blob/main/MVTec%20AD-C.png)

Introduction
---
The automation of quality control is common and plays a major role in many industries. [MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad) is an excellent dataset for benchmarking anomaly detection (AD) methods. Researchers have made some achievements by unremitting efforts, and we are fortunate to witness the progress of anomaly detection algorithms ([Paper](https://link.springer.com/content/pdf/10.1007/s11263-020-01400-4.pdf), [Paper with code](https://paperswithcode.com/sota/anomaly-detection-on-mvtec-ad), [Anomalib](https://github.com/openvinotoolkit/anomalib/tree/feature/fastflow)).

Although existing state-of-the-art anomaly detection methods get good results on the detection and segmentation task, **we notice that there are few studies about the model robustness**, i.e. the performance on the corrupted data. This repository contains the corrupted MVTec anomaly detection dataset for benchmarking AD model robustness.

Our MVTec AD-C dataset consists of the original data and 6 types of algorithmically generated corruptions.  
(a) Original image; (b) Defocus blur; (c) Gaussian blur; (d) Dropout pixels; (e) Gaussian noise; (f) Poisson noise; (g) Salt and pepper noise.  
**Appendix A** gives the detail of implementation corruptions. **Appendix B** provide results of some state-of-the-art anomaly detection methods.

Dataset description
---
Download linke: [Google Drive](https://drive.google.com/drive/folders/1g95--YXVdar5ny9GJbFlgpxZh4SusaJZ?usp=sharing), [Baidu Netdisk (Password: 7897)](https://pan.baidu.com/s/1PVeGeJx5n1fNGiLdOSrevA).  
The training set and groun truth is as same as the [MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad).  
Image size: 512 x 512.  


---
If you have any questions at all, please feel free to tell us (email: chenyurong1998@outlook.com).  
**Acknowledgement:** We would like to thank Ms. Yang for discussing, providing the insight and conducting experiments.  

---
![contents](https://github.com/YurongChen1998/MVTec-AD-C/blob/main/Wide-ResNet50.pdf)
