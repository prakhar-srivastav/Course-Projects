# The objective

the idea is to detect abnormal activity in the surveillence video camera by traning the auto-encoder on large amount of normal scenes as compared to abnormal scenes. The auto-encoder will reconstruct the sequence .While reconstructing , it will only consider the most repeated events and ignore the abnormal activity.
We will identify the activity as abnormal if there is a cart or a biker presence in a scene or if a person is found walking on a grass.

![steps](https://user-images.githubusercontent.com/28844605/85394359-187a8700-b56c-11ea-8679-4c61c01493e8.JPG)

# Dataset used

The dataset used is from UCSD Anomaly Detection Dataset
(http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)


![vidf4_33_007_frame080_mark](https://user-images.githubusercontent.com/28844605/84398862-13d5da80-ac1e-11ea-873d-5d18cb5503db.png)
![vidf1_33_002_frame138_mark](https://user-images.githubusercontent.com/28844605/84398814-07ea1880-ac1e-11ea-94de-2efcab2e856b.png)

Model Architecture-

![1_rycekfrT7rx6XdZsyB0I6w](https://user-images.githubusercontent.com/28844605/84399433-7af38f00-ac1e-11ea-9995-6cfe6c60d69f.jpeg)

Following are some useful links related to this project: 
Normalization-https://mlexplained.com/2018/11/30/an-overview-of-normalization-methods-in-deep-learning/
Timedistributed layer|:https://machinelearningmastery.com/timedistributed-layer-for-long-short-term-memory-networks-in-python/
https://stackoverflow.com/questions/42755820/how-to-use-return-sequences-option-and-timedistributed-layer-in-keras
https://www.dlology.com/blog/how-to-use-return_state-or-return_sequences-in-keras/

Transposed Convolution:https://www.youtube.com/watch?v=96_oGE8WyPg
