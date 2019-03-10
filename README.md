# Face-Anti-spoofing

depend on pytorch1.0  and fastai

source code files:

1、dataset_process.ipynb
 
 data sets is prepared  like this:
 
 train/fake/image files
 train/true/image files
 val/fake/image files
 val/true/image files
 
 
 
2、first_train.ipynb

 #training...


3、predict.ipynb
 
# predict results of test set


trained models:

1、best_model1.pkl 
(trained only on train data sets)

2、best_model2.pkl
(trained on train datasets and test data sets, just add the test data sets to the train sets using the label predicted by best_model1.pkl )

predicted results of test set：

1、 9987last_result_for_Test.zip   (predicted by best_model1.pkl)

2、 try3_10_last_result_for_Test.zip (predicted by best_model2.pkl)
