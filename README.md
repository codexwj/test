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
### Setup enviroment <br>
''' <br>
conda create -n TianChi python=3.6 <br>
source activate TianChi <br>
pip install -r requirements.txt <br>
''' <br>


### Training and Testing <br>
1.Assume the train and test dataset are located ar `'data/'` <br>
2.Run: <br>
-find path <br>
----step 1: cd code <br>
-segmentation two big images <br>
----step 2: python genData_blog.py <br>
-data augmentation <br>
----step 3: python GenDatasetClass.py <br>
-for train model <br>
----step 4: python train.py <br>
-for test, result is saved in submit directory <br>
----step 5: python predict.py


