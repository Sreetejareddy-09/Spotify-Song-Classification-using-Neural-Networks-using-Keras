# Spotify Song Classification using Neural Networks (Keras)

This project involves building, training, and evaluating a neural network using Keras to classify songs from the Spotify dataset. The goal is to predict whether a song will make it to the Billboard Hot-100 list based on 15 audio features. The dataset contains 6,398 tracks, with binary labels (1 = made it to Hot-100, 0 = did not make it).

## Key Steps
1. **Data Preparation**:
   - Shuffled and split the dataset into training (90%), validation (20% of training), and test sets (10%).
2. **Model Building**:
   - Built a neural network with 2 hidden layers (32 nodes each) and 1 output unit.
3. **Model Training**:
   - Compiled the model using binary cross-entropy loss and SGD optimizer (learning rate = 0.01).
   - Trained the model for 50 epochs with a batch size of 16.
4. **Model Evaluation**:
   - Evaluated the model on training and validation sets.
   - Plotted the learning curve (training vs. validation loss).
5. **Experimentation**:
   - Experimented with different architectures and hyperparameters (e.g., 64 nodes in the first layer, Adam optimizer, 100 epochs, batch size = 32).
6. **Final Evaluation**:
   - Selected the best model based on validation accuracy.
   - Evaluated the best model on the test set and reported test loss and accuracy.

## Tools Used
- Python
- TensorFlow/Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Repository Contents
- Code for data preprocessing, model building, training, and evaluation.
- Learning curve plots.
- Results (training, validation, and test accuracy/loss).

## How to Run the Code
1. Upload the `spotify_preprocessed.csv` file to Google Colab or your local environment.
2. Run the code blocks sequentially in the provided notebook.
3. View the results, including accuracy, loss, and learning curves.

## Results
- **Initial Model**:
  - Training Accuracy: 0.92
  - Validation Accuracy: 0.88
- **Modified Model**:
  - Training Accuracy: 0.94
  - Validation Accuracy: 0.90
- **Best Model**:
  - Test Loss: 0.25
  - Test Accuracy: 0.91

---

Feel free to contribute or suggest improvements!
