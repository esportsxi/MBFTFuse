# MBFTFuse
## MBFTFuse:A Dual-stream Adversarial Network Based on Modality Balancing and Feature Tracing Compensation for Infrared and Visible Image Fusion

### Code Description
Our paper is currently in the review stage, and paper data will be made public after the paper is published
The dataset used in the paper is as follows：

[TNO](https://figshare.com/articles/dataset/TNO_Image_Fusion_Dataset/1008029/2)

[MRSR](https://github.com/Linfeng-Tang/MSRS)

[RoadScene](https://github.com/hanna-xu/RoadScene)

Thank you to the contributors of the open source community for their contributions.

### Code usage instructions
- Replace your own dataset and modify hyperparameters in the *args.py*
Modify the training dataset address
```
train_ir = ''
train_vi = ''
```
Modify the saving path of the model and loss
```
save_model_dir = ''
save_loss_dir = ''
```
Modify the  path of test model and test imgs dir
```
test_model_name = ''
test_imgs_dir= ''
```
train
```python
run main.py flag = 1
```
test
```
run main.py flag = 0
```

- We are currently developing a dataset of infrared and visible light drone images, which will be open sourced to the community in the future. Scholars are welcome to stay tuned
