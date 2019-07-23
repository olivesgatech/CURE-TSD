# CURE-TSD
CURE-TSD: Challenging Unreal and Real Environments for Traffic Sign Detection




| <a href="http://www.youtube.com/watch?feature=player_embedded&v=8V1LcpDlmjA
" target="_blank"><img src="http://img.youtube.com/vi/8V1LcpDlmjA/0.jpg" 
alt="CURE-TSD Real" width="240" height="180" border="10" /></a> 
|
<a href="http://www.youtube.com/watch?feature=player_embedded&v=bKnlJ_EWS8Q
" target="_blank"><img src="http://img.youtube.com/vi/bKnlJ_EWS8Q/0.jpg" 
alt="CURE-TSD Unreal" width="240" height="180" border="10" /></a> 
|

  



### Publications
If you use CURE-TSD dataset or codes, please cite:

   
 [Challenging Environments for Traffic Sign Detection: Reliability Assessment under Inclement Conditions](https://arxiv.org/abs/1902.06857)

```
@INPROCEEDINGS{Temel2019,
author = {D. Temel and T. Alshawi and M.-H. Chen and G. AlRegib},
booktitle={arXiv:1902.06857},
title = {Challenging Environments for Traffic Sign Detection: Reliability Assessment under Inclement Conditions},
year = {2015},
}
```

 [Traffic Signs in the Wild: Highlights from the IEEE Video and Image Processing Cup 2017 Student Competition [SP Competitions]
](https://arxiv.org/abs/1810.06169)

```
@ARTICLE{Temel2018_SPM,
author={D. Temel and G. AlRegib},
journal={IEEE Sig. Proc. Mag.},
title={Traffic Signs in the Wild: Highlights from the IEEE Video and Image Processing Cup 2017 Student
Competition [SP Competitions]},
year={2018},
volume={35},
number={2},
pages={154-161},
doi={10.1109/MSP.2017.2783449},
ISSN={1053-5888},}
```
 [CURE-TSR: Challenging unreal and real environments for traffic sign recognition](https://arxiv.org/abs/1712.02463)
  
```
@INPROCEEDINGS{Temel2017_NIPSW,
Author = {D. Temel and G. Kwon and M. Prabhushankar and G. AlRegib},
Title = {{CURE-TSR: Challenging unreal and real environments for traffic sign recognition}},
Year = {2017},
booktitle = {Neural Information Processing Systems (NeurIPS) Workshop on Machine Learning for Intelligent Transportation Systems},

```



### Download Dataset
The video sequences in the CURE-TSD dataset are grouped into two classes: real data and unreal data. Real data correspond to processed versions of sequences acquired from real world. Unreal data corresponds to synthesized sequences generated in a virtual environment. There are 49 real sequences and 49 unreal sequences that do not include any specific challenge. We separated the sequences into 70% and %30 splits. Therefore, we have 34 training videos and 15 test videos in both real and unreal sequences that are challenge-free. There are 300 frames in each video sequence. There are 49 challenge-free real video sequences processed with 12 different types of effects and 5 different challenge levels, which result in 2,989 (49*12*5+49) video sequences. Moreover, there are 49 synthesized video sequences processed with 11 different types of effects and 5 different challenge levels, which leads to 2,744 (49*11*5+49) video sequences. In total, there are 5,733 video sequences, which include around 1.72 million frames. To receive  the download link, please fill out this <strong><a href="https://docs.google.com/forms/d/e/1FAIpQLScF3TO-2xhMmIc-GibKb8DBnwC6knSqew68zeRWurortg1pKg/viewform">FORM</a></strong> to submit your information and agree the conditions of use. These information will be kept confidential and will not be released to anybody outside the MSL administration team.

### Challenging Conditions
<p align="center">
<img src="./Images/curetsd_challenges.png">
</p>

### Traffic Signs
<p align="center">
<img src="./Images/sign_types.png">
</p>

### File Name Format
“sequenceType_sequenceNumber_challengeSourceType_challengeType_challengeLevel.txt”

* sequenceType:
01 – Real data
02 – Unreal data

* sequenceNumber:
A number in between [01 – 49]

* challengeSourceType:
00 – No challenge source (which means no challenge)
01 – After affect

* challengeType:
00 – No challenge
01 – Decolorization
02 – Lens blur
03 – Codec error
04 – Darkening
05 – Dirty lens
06 – Exposure
07 – Gaussian blur
08 – Noise
09 – Rain
10 – Shadow
11 – Snow
12 – Haze

* challengeLevel:
A number in between [01-05] where 01 is the least severe and 05 is the most severe challenge.

### Test Sequences
We split the video sequences into 70% training set and 30% test set. The sequence numbers corresponding to test set are given below:

[01_04_x_x_x, 01_05_x_x_x, 01_06_x_x_x, 01_07_x_x_x, 01_08_x_x_x, 01_18_x_x_x, 01_19_x_x_x, 01_21_x_x_x, 01_24_x_x_x, 01_26_x_x_x, 01_31_x_x_x, 01_38_x_x_x, 01_39_x_x_x, 01_41_x_x_x, 01_47_x_x_x, 02_02_x_x_x, 02_04_x_x_x, 02_06_x_x_x, 02_09_x_x_x, 02_12_x_x_x, 02_13_x_x_x, 02_16_x_x_x, 02_17_x_x_x, 02_18_x_x_x, 02_20_x_x_x, 02_22_x_x_x, 02_28_x_x_x, 02_31_x_x_x, 02_32_x_x_x, 02_36_x_x_x]

The videos with all other sequence numbers are in the training set.
Note that “x” above refers to the variations listed earlier.

