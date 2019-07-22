2019年县域农业AI挑战赛
===================
project structure
-------------------
>project <br>
>> README.md <br>
>> data <br>
>> code <br>
>> submit <br>
>> requirement.txt <br>

How It works
------------------
This code has been trained on Ubuntu 16.04, Python 3.6, Pytorch 1.0, CUDA 9.1, RTX Titai Xp GPU <br>
##Setup enviroment
''' <br>
conda create -n TianChi python=3.6 <br>
source activate TianChi <br>
pip install -r requirements.txt <br>
''' <br>


##Training the Model <br>
1.Assume the train and test dataset are located ar `'data/'` <br>
2.Run: <br>
----step 1: cd code <br>
----step 2: python genData_blog.py <br>
# segmentation two big images
----step 3: python GenDatasetClass.py <br>
# data augmentation
----step 4: python train.py <br>
# train model
----step 5: python predict.py
# for test, result is saved in submit directory

