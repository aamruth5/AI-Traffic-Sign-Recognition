# Traffic Sign recognition Using CNN 
**Dataset used: [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset).
This dataset has more than 50,000 images of 43 classes.**

## Pipeline architecture:
- **Load The Data.**
- **Dataset Summary & Exploration**
- **Data Preprocessing**.
- **Design a Model Architecture.**
- **Model Training and Evaluation.**
- **Testing the Model Using the Test Set.**
- **Testing the Model on New Images.**

---
- **Model Architecture Design**
ConvNet follows these steps:
**Layer 1 (Convolutional):** The output shape should be 28x28x6.
**Activation.** Your choice of activation function.
**Pooling.** The output shape should be 14x14x6.

**Layer 2 (Convolutional):** The output shape should be 10x10x16.
**Activation.** Your choice of activation function.
**Pooling.** The output shape should be 5x5x16.
**Flattening:** Flatten the output shape of the final pooling layer such that it's 1D instead of 3D.

**Layer 3 (Fully Connected):** This should have 120 outputs.
**Activation.** Your choice of activation function.

**Layer 4 (Fully Connected):** This should have 84 outputs.
**Activation.** Your choice of activation function.

**Layer 5 (Fully Connected):** This should have 10 outputs.

Other ConvNet follows these steps:

**Layer 1 (Convolutional):** The output shape should be 32x32x32.
**Activation.** Your choice of activation function.

**Layer 2 (Convolutional):** The output shape should be 32x32x32.
**Activation.** Your choice of activation function.

**Layer 3 (Pooling)** The output shape should be 16x16x32.

**Layer 4 (Convolutional):** The output shape should be 16x16x64.
**Activation.** Your choice of activation function.

**Layer 5 (Convolutional):** The output shape should be 16x16x64.
**Activation.** Your choice of activation function.

**Layer 6 (Pooling)** The output shape should be 8x8x64.

**Layer 7 (Convolutional):** The output shape should be 8x8x128.
**Activation.** Your choice of activation function.

**Layer 8 (Convolutional):** The output shape should be 8x8x128.
**Activation.** Your choice of activation function.

**Layer 9 (Pooling)** The output shape should be 4x4x128.
**Flattening:** Flatten the output shape of the final pooling layer such that it's 1D instead of 3D.

**Layer 10 (Fully Connected):** This should have 128 outputs.
**Activation.** Your choice of activation function.

**Layer 11 (Fully Connected):** This should have 128 outputs.
**Activation.** Your choice of activation function.

**Layer 12 (Fully Connected):** This should have 43 outputs.

