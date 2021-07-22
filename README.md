# Neural Network Anime Character Classifier

Training a Neural Network model in Deep Learningto classify 7 anime charaters in Onepiece. 


**Mainly Used Library**
- tensorflow
- numpy
- matplotlib

**Deep Learning**
- Neural Network type: VGG-16
- Built-in layers: 5 blocks of layers
- Layers type: Conv2D, MaxPooling2D, Dense, Flatten
- Output the result with softmax activation

**Procedure**
1. Load the data from `onepiece_images` folder
2. Visualize the image dataset in subplots
3. Re-validating the data shape
4. Shuffle and configure the dataset 
5. Preprocess the dataset
6. Build the VGG-16 model
7. Train the model by 20 epoches
8. Plot the training and validation loss to evaluate the performance
