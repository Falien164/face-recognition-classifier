# face-recognition-classifier
face recognition classifier with TensorFlow

### How to use
First dataset should be download and split into training and validation folder. In each folder should be subfolders of classes to classify. Number of subfolders should be the same in both folders. If you want to extract faces from images use Extract_faces.ipynb.


### Comparission of two models
Simple CNN model:
```
[2 1 0 0 2]                     
[0 5 0 0 0]                     
[0 0 4 0 1]                     
[0 1 0 4 0]                     
[0 0 1 0 4]                     
```
VGG16 model with transfer learning:
```
[5 0 0 0 0]
[0 5 0 0 0]
[0 0 5 0 0]
[0 0 0 5 0]
[1 0 0 0 4]
```
### results of VGG16 model on LFW dataset
avg_weighted prediction - 0.75
avg_weighted recall 0.58
avg_weighted f1-score - 0.60
