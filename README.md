# Amex_Binary_tabular_data
This was my work for the America Express Default Predictioon competition held by Kaggle : https://www.kaggle.com/competitions/amex-default-prediction

In this project, I undertook the task of analyzing tabular data that exhibited significant class imbalance. Upon reflection, it would have been prudent to employ weighted initialization for each class during the training phase. However, at the time, my attempts at upsampling proved to be ineffective in mitigating the issue adequately.

Considering the circumstances, I invested considerable effort in implementing a Deep Neural Network (DNN) methodology. Eventually, after thorough experimentation, I opted to submit an optimized variant of a pre-existing notebook utilizing LightGBM (LGBM), which was adapted to suit the specific requirements of the project.
