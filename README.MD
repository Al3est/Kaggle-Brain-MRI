
# Brain MRI

### Overview

This code is used for practice Pytorch lightning with [Kaggle Brain MRI Dataset.](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

### File Structure

```
.
├── brain_mri.ipynb
└── README.MD

```

### File Description

- **brain_mri.ipynb**: This file is notebook file that contain the code that used for practice
  -  Function
     -  create_metadata: Function to create metadata for this dataset.
     -  train_val_test_split: Function used for split dataset into train dataset, validation dataset and test dataset (return as dataset index)
     -  prepare_dataloader: Function used for prepare dataloader of  dataset.
  - Class
    - BrainMRIDataset: Custom Pytorch dataset for this dataset.
    - Model: Custom Pytorch lightning class for models that use it for classification images.
- **README.MD**