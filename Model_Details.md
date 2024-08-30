## Model 1
- Flatten layer (784)
- Dense layer (256)(relu)
- Dense layer (128)(relu)
- Dropout (0.45)
- Dense layer (62)(Output)(softmax)

## Model 2
- Conv2D layer (32)(kernel = 5)(relu)
- MaxPool2D layer
- Dropout (0.3)
- Flatten
- Dense Layer(128)(relu)
- Dense Layer (62)(output)(softmax)

## Model 3
- Conv2D (32)(kernel = 3)
- MaxPool2D
- BatchNormalization()
- Conv2D (64)(kernel = 3)
- BatchNormalization()
- MaxPool2D
- BatchNormalization()
- Conv2D (256)(kernel = 3)
- BatchNormalization()
- Conv2D (256)(kernel = 3)
- GlobalAvgPool2D
- Dense (256)(relu)
- Dense (62)(softmax)
