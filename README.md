# SVMExample
1. 在开源的车牌识别系统EasyPR中，用SVM（支持向量机）模型甄选出候选车牌中真正的车牌。目前EasyPR1.4的SVM模型输入的是LBP特征，本代码将EasyPR的svm_train.cpp独立出来，包含SIFT和SURF结合BOW作为SVM输入，以及LBP和HOG特征作为SVM的输入。
2. 例程要求在当前项目的工程文件.vcproj相同目录下有一个名为param.xml的文件，目前例程中有一个现成的文件。该文件中包含程序产生的文件存储路径，切换特征点类型，BOW词汇表的总量等参数均需要在此文件中设置。
