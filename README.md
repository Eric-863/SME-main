I. Dataset
Link: https://pan.baidu.com/s/1VcednLdgcgMlBwqULB4LnQ?pwd=sfi3
Extraction Code: sfi3

II. Training
1. Put the provided dataset into VOCdevkit/VOC2007.
2. Set the corresponding parameters in train.py. The default parameters already match those required by the dataset.
3. Run train.py to start the training.

III. Prediction
1. Settings can be made in predict.py for fps testing, testing of an entire folder, and video detection.
2. In the deeplab.py file, modify model_path, num_classes, and backbone in the following part to match the trained files. **model_path corresponds to the weight file in the logs folder. num_classes represents the number of classes to be predicted plus 1.
