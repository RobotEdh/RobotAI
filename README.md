# RobotAI
Artificial Intelligence
## 1 - Deep Neural Network

**Layers**: Relu->Relu->Relu->Sigmoid + Dropout

**Loss**: BinaryCrossentropy

**Optimizer**: Adam

**Dataset**: catvnoncat

###### - train_x's shape: (209, 12288)
###### - test_x's shape: (50, 12288)
###### - train_y's shape: (209, 1)
###### - test_y's shape: (50, 1)

## 2 - CNN

**Layers**: Conv2D->MaxPool2D->Conv2D->MaxPool2D->FC->Softmax

**Loss**:CategoricalCrossentropy

**Optimizer**: Adam

**Dataset**: signs

###### - train_x shape: (1080, 64, 64, 3)
###### - train_y shape: (1080, 6)
###### - test_x shape: (120, 64, 64, 3)
###### - test_y shape: (120, 6)

## 3 - ResNet (Residual Network)

**Layers**: ResNet50 model

**Loss**:?

**Optimizer**: ?

**Dataset**: signs

###### - train_x shape: (1080, 64, 64, 3)
###### - train_y shape: (1080, 6)
###### - test_x shape: (120, 64, 64, 3)
###### - test_y shape: (120, 6)

## 4 - Yolo

**Layers**: yolov3 model

**Loss**:?

**Optimizer**: ?

**Dataset**: ?

###### - input imgage (1, 416, 416, 3)
###### - output model [(1, 13, 13, 255), (1, 26, 26, 255), (1, 52, 52, 255)]
###### [255, 255, 255] = ( 80 classes + pc,bx,by,bh,bw ) * 3 anchor boxes


