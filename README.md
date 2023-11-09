# Malaria Detection from Cell Images

**Group Number:** 17

Overview:
----------
This project helps to detect malaria infected cells from unparasitized cells from cell images. Project demonstration can be viewed from the following [demonstration video](https://www.loom.com/share/ab43e675fb1b49cb9aeba9b5742340c1)

Team Members:
--------------
1)Shrestha Datta (2018331030)<br/>
2)Zhalok Rahman (2018331046)<br/>
3)Joydip Saha (2018331108)<br/>
4)Fahmida Akter (2018331122)<br/>
5)Suraiya Akter Eva (2018331048)

Dataset Link:
---------------
Source: kaggle [Malaria Dataset](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria)

Splitting Dataset:
---------------
Source code to split dataset is in [Dataset Splitting.ipynb](https://github.com/cse-338-2018/project-group_17/blob/main/Malaria_Detection_Model_bulding_and_analysis/Dataset%20Splitting.ipynb) jupyter notebook file under the folder 'Malaria_Detection_Model_bulding_and_analysis'.

Pipelines for the models:
-------------------------
The pipelines for the models including model building, saving model, training model, model analysis, data preprocessing, predicting a single cell image, are in the files under the folder 'Malaria_Detection_Model_bulding_and_analysis':
- CNN model with accuracy 96.08% [Custom CNN model.ipynb](https://github.com/cse-338-2018/project-group_17/blob/main/Malaria_Detection_Model_bulding_and_analysis/custom%20CNN%20model.ipynb)
- CNN model V2 with accuracy 96.33% [CNN model V2.ipynb](https://github.com/cse-338-2018/project-group_17/blob/main/Malaria_Detection_Model_bulding_and_analysis/CNN%20model%20V2.ipynb)
- Transfer learning model based on VGG19 with accuray 92.67% [Transfer Learning model using VGG19.ipynb](https://github.com/cse-338-2018/project-group_17/blob/main/Malaria_Detection_Model_bulding_and_analysis/Transfer%20Learning%20model%20using%20VGG19.ipynb)

Visulizing the filters at each convolution layers:
--------------------------------------------------
The Visualization of the Filters of convolution layers used in CNN are in file [Custom CNN model convolution features.ipynb](https://github.com/cse-338-2018/project-group_17/blob/main/Malaria_Detection_Model_bulding_and_analysis/Custom%20CNN%20model%20convolution%20features.ipynb) under the folder 'Malaria_Detection_Model_bulding_and_analysis'.

How to run Backend:
------------------
Instructions to run backend can be found in the following [directory](https://github.com/cse-338-2018/project-group_17/blob/main/Application/back-end).

How to run Frontend:
-------------------
Instructions to run frontend can be found in the following [directory](https://github.com/cse-338-2018/project-group_17/blob/main/Application/front-end).
