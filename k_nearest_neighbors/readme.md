## HIS data Classification by knn(k近邻) classfier

Here, we illustriate some datasets and use svm for classification task.
For per category, we selected 200 samples randomly for training, and others for testing.

And the performence I may didn't find the best parpmeters, and her set the number of neighbor as 10.

### result
- Indian_pines
    - overall accuracy 68.79%
    - kappa 63.60%
    - decode map
    ![decode_map](result/decode_resultInidan_pines.png)
    ![fusion_matrix](result/confusion_matrix1Inidan_pines.png)


- PaviaU
    - overall accuracy 79.21%
    - kappa 72.75%
    - decode map
    ![decode_map](result/decode_resultPaviaU.png)
    ![fusion_matrix](result/confusion_matrix1PaviaU.png)
- Salinas
- overall accuracy 86.35%
    - kappa 84.76%
    - decode map
    ![decode_map](result/decode_resultSalinas.png)
    ![fusion_matrix](result/confusion_matrix1Salinas.png)
