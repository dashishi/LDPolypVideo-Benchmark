# LDPolypVideo-Benchmark
A public endoscopic video dataset for polyp detection
### Abstract
Computer-Aided Diagnosis (CAD) systems for polyp detection provide essential support for colorectal cancer screening and prevention. 
Recently, deep learning technology has made breakthrough progress in medical image computation and computer-aided diagnosis. However, the deficiency of training data seriously impedes the development of polyp detection techniques. 
Existing fully-annotated databases, including CVC-ClinicDB, ETIS-Larib, CVC-Colon dataset, Kvasir-Seg, and CVC-ClinicVideoDB, are very limited in polyp size and shape diversity, which is far from the significant complexity in the actual clinical situation. 
In this paper, we propose LDPolypVideo, a large-scale colonoscopy video database that contains a variety of polyps and more complex bowel environments. 
Our database contains 160 colonoscopy videos and 40,266 frames in total with polyp annotations, which are four times the size of the largest existing colonoscopy video database CVC-ClinicVideoDB. 
In order to improve the efficiency of polyp annotation, we design an intelligent annotation tool based on object tracking. 
Extensive experiments have been conducted to evaluate state-of-the-art object detection approaches on our LDPolypVideo dataset. The average drops of Recall and Precision of four SOTA approaches on this dataset are 26\% and 15\%, respectively. 
The great performance drop demonstrates the significant challenges but also the great value of our large-scale and diverse polyp video dataset to facilitate the research on polyp detection.

### Overview of dataset
In order to increase the size and diversity of colonoscopy data for training and evaluation of polyp detection approaches, we present a large-scale and diverse colonoscopy video dataset named LDPolyVideo.
It consists of 160 videos with 40,266 frames, nearly four times the size of the largest existing fully-annotated dataset.
There are 33,884 frames that contain at least one polyp and in total 200 labeled polyps, which are more than 11 times the polyps in CVC-ClinicVideoDB.
The polyps present more diverse morphologies.
Fig.1 shows a set of example images and the annotated masks for polyps.
Besides, we also provide 103 videos, including 861,400 frames without full annotations. Each video has a label indicating whether it contains polyps. 
These videos enrich the data diversity and will support unsupervised and semi-supervised methods.
Based on our LDPolyVideo dataset, we evaluate a number of state-of-the-art approaches for polyp detection to analyze their strengths and weaknesses, demonstrating the challenges of colonoscopy polyp detection in clinical examination.

![data example](https://github.com/dashishi/LDPolypVideo-Benchmark/blob/main/images/dataset-examples.jpg)

![summary](https://github.com/dashishi/LDPolypVideo-Benchmark/blob/main/images/summary.jpg)
### Citation
> Yiting. Ma, Xuejin. Chen, Kai. Cheng, Yang. Li and Bin. Sun. "LDPolypVideo Benchmark: A Large-scale Colonoscopy Video Dataset of Diverse Polyps", Medical Image Computing and Computer Assisted Intervention Society, 2021

### Download
[Click here to download the whole dataset](https://pan.baidu.com/s/1so6Sj1FJ87vsipWLpCSscA)

Extraction code: ustc
