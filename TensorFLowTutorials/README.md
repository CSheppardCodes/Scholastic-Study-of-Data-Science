# TensorFlow Tutorials with modified code


# Image Classification Tutorial 

This tutorial covers the end-to-end process of creating an image classification model using TensorFlow:

1. **Data Setup:**
   - Flower dataset with 3,700 images in five categories.

2. **Model Building:**
   - Basic CNN using `tf.keras.Sequential`.
   - Compiled with Adam optimizer, sparse categorical crossentropy loss.

3. **Training:**
   - Initial training for 10 epochs, revealing overfitting.
   - Implemented data augmentation and dropout.

4. **Improved Training:**
   - Retrained the model with augmented data, reducing overfitting.

5. **Inference and Evaluation:**
   - Performed inference on a new image.

6. **Conclusion:**
   - Emphasizes key steps and techniques for better model performance.

This concise tutorial is a guide for creating, training, and deploying an image classification model with TensorFlow, highlighting strategies to enhance accuracy and prevent overfitting.


# Text Classification with Transfer Learning

This concise tutorial guides you through text classification using transfer learning with TensorFlow and Keras, focusing on movie reviews from the IMDB dataset.

## Key Steps

1. **Data Loading:** Use the balanced IMDB dataset (25,000 reviews each for training and testing).

2. **Model Building:** Create a neural network with a pre-trained text embedding (Google's NNLM) and dense layers.

3. **Text Representation:** Leverage transfer learning for text embeddings, simplifying preprocessing and ensuring fixed-size outputs.

4. **Model Structure:** Stack layers with a TensorFlow Hub layer, a dense layer (16 hidden units), and a final output layer.

5. **Training:** Train for 10 epochs, monitor with validation data, and use binary crossentropy loss.

6. **Evaluation:** Achieve around 87% accuracy on the test dataset.

## Results and Insights

- Transfer learning simplifies text representation and provides a fixed-size output.
- Model architecture decisions impact performance (e.g., number of layers, hidden units).
- Binary crossentropy loss and Adam optimizer are effective for this binary classification task.

## Next Steps

Explore advanced techniques for improved accuracy, aiming for a target of 95%. For more details, refer to the [MLCC Text Classification Guide](#) and other TFHub text-related tutorials.
