# CSE597-CV
CSE597 Final Project 

# Dataset
The MSVD-QA dataset is used to replicate the results in this project. The dataset and the pre-computed features can be found at: https://github.com/doc-doc/NExT-QA

Please download the following files:
1. 'vid_feat.zip'
2. 'qas_bert.zip'
3. 'nextqa.zip'

After downloading the dataset, modify the paths accordingly.

# Replication
Run train.sh to replicate the results in the paper. The saved checkpoint model can be found here:
https://drive.google.com/file/d/1oQfLa9ZIjiYTM8Dw8vEFNylgifsv4hYf/view

# Hyperparameter Tuning
For hyperparameter tuning, make changes in the run.py file.

# Reference
@InProceedings{Li_2022_CVPR,
    author    = {Li, Yicong and Wang, Xiang and Xiao, Junbin and Ji, Wei and Chua, Tat-Seng},
    title     = {Invariant Grounding for Video Question Answering},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {2928-2937}
}

This repository is a replication of the original repository of the above referenced paper.