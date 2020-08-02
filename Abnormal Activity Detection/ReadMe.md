# The objective

The high level idea is to detect anomaly in the video sequence by using auto-encoder model architecture. The dataset contained normal scene as well as abnormal scene. The normal scene are present in abundent while abnormal scene are rare. This is the motivation behind using unsupervised mode of learning for this task.

![steps](https://user-images.githubusercontent.com/28844605/85394359-187a8700-b56c-11ea-8679-4c61c01493e8.JPG)

# Dataset used

The dataset used is from UCSD Anomaly Detection Dataset
(http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)


![vidf4_33_007_frame080_mark](https://user-images.githubusercontent.com/28844605/84398862-13d5da80-ac1e-11ea-873d-5d18cb5503db.png)
![vidf1_33_002_frame138_mark](https://user-images.githubusercontent.com/28844605/84398814-07ea1880-ac1e-11ea-94de-2efcab2e856b.png)

# Model Architecture-

![model](https://user-images.githubusercontent.com/28844605/89119704-13dfb180-d4ce-11ea-8e40-040739672b99.jpeg)
Complete Model  Architecture

# Original and Reconstructed sequences-
![temp1](https://user-images.githubusercontent.com/28844605/89119766-6a4cf000-d4ce-11ea-9a27-f5d689ccba53.PNG)
![temp2](https://user-images.githubusercontent.com/28844605/89119793-8e103600-d4ce-11ea-9501-edb26b17e180.PNG)



Following are some useful links related to this project: 
Normalization-https://mlexplained.com/2018/11/30/an-overview-of-normalization-methods-in-deep-learning/
Timedistributed layer|:https://machinelearningmastery.com/timedistributed-layer-for-long-short-term-memory-networks-in-python/
https://stackoverflow.com/questions/42755820/how-to-use-return-sequences-option-and-timedistributed-layer-in-keras
https://www.dlology.com/blog/how-to-use-return_state-or-return_sequences-in-keras/
Transposed Convolution:https://www.youtube.com/watch?v=96_oGE8WyPg
