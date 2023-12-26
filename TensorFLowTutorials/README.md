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



# Sentiment Analysis with RNNs

This concise tutorial demonstrates sentiment analysis on the IMDB movie review dataset using TensorFlow's recurrent neural networks (RNNs).

1. **Data Handling:**
   - Load and batch the IMDB dataset for sentiment analysis.

2. **Text Processing:**
   - Utilize the TextVectorization layer for text encoding.

3. **Model Architecture:**
   - Create a sequential model with text encoding, embedding, bidirectional LSTM, and dense layers.

4. **Training and Evaluation:**
   - Train the model for 10 epochs, achieving ~85% accuracy on sentiment analysis.
   - Explore an advanced model with stacked bidirectional LSTM layers, boosting accuracy to ~86%.

5. **Inference:**
   - Make predictions on new sentences for sentiment analysis.

6. **Recommendations:**
   - Experiment with other recurrent layers like GRU.
   - Explore custom RNN architectures using the Keras RNN Guide.

This tutorial offers a streamlined approach to sentiment analysis using RNNs, emphasizing practical insights and model improvements.

- Transfer learning simplifies text representation and provides a fixed-size output.
- Model architecture decisions impact performance (e.g., number of layers, hidden units).
- Binary crossentropy loss and Adam optimizer are effective for this binary classification task.

## Next Steps

Explore advanced techniques for improved accuracy, aiming for a target of 95%. For more details, refer to the [MLCC Text Classification Guide](#) and other TFHub text-related tutorials.


# TensorFlow Hub Transfer Learning

1. **Prerequisites:**
   -  Essential libraries: NumPy, PIL, Matplotlib, TensorFlow, TensorFlow Hub, Datetime.

2. **Image Classification:**
   -  Utilize pre-trained ImageNet classifiers (e.g., MobileNetV2, InceptionV3).
   -  **Single Image Evaluation:** Download and predict using pre-trained models.

3. **Simple Transfer Learning:**
   -  **Custom Classifier with Flowers Dataset:** Load and preprocess data efficiently.
   -  **Data Preprocessing:** Normalize input data for enhanced training.
   -  **Batch Image Classification:** Train on custom dataset, visualize predictions.

4. **Transfer Learning with Custom Classifier:**
   - **Feature Extraction:** Construct a headless model for efficient transfer learning.
   - **Classification Head Integration:** Complete the transfer learning model.
   - **Model Training:** Compile, train, and monitor with TensorBoard.
   - **TensorBoard Visualization:** Utilize TensorBoard for detailed progress.
      ![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/2312c1c2-ab55-4b5d-9a8c-30cfa608518e)

5. **Model Evaluation and Export:**
   - **Predictive Analysis:** Evaluate and visualize batch predictions.
   - **Model Export and Reload:** Persist the model for future use.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/b1fd8216-f5b8-4b11-9094-3aa4f7348776)

# Conclusion

This tutorial highlights TensorFlow Hub's efficiency in transfer learning for image classification. It guides users through essential steps, from model customization to efficient training and evaluation, showcasing TensorFlow Hub's diverse applications.

