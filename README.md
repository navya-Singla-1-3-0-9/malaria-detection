# malaria-detection
## Snapshot
![image](https://user-images.githubusercontent.com/90545403/199651335-f505678f-8b72-440f-9d9f-c07a21796ba0.png)

## About the app
This is a system that is used to detect the parasites of malaria from the blood smears.
- The dataset is collected from Kaggle which consists of 27,558 images. These images are divided into two classes named as parasitized and uninfected. Both of these classes consist of 13779 images.
- After splitting data into train and test then we choose the CNN algorithm for classifying the data. We give the train data to the CNN algorithm by making use of the fit function and train the algorithm to detect the malaria disease.
![image](https://user-images.githubusercontent.com/90545403/199651026-03c06663-54cd-48d2-b9c2-68bbe224b5d7.png)

## Performance and Loss function
Since in the dataset the number of samples from each target class is equal, we consider accuracy as our primary metric.
We have used binary cross entropy or log-loss, and the target is to minimize it which is
equivalent to maximize the classification accuracy.
![image](https://user-images.githubusercontent.com/90545403/199651160-8e32f541-ca71-482e-a622-b2407364a60f.png)
