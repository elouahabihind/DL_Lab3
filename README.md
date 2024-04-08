# Fine-Tuning GPT-2 on a Jokes Dataset

The goal here was to fine-tune a pre-trained medium-sized GPT-2 model on a dataset of jokes to assess its ability to generate humorous content.

## Process Overview:

1. **Dataset Preparation:** Utilized the Short Jokes dataset from Kaggle, preprocessing each joke with a special end-of-text marker to help the model generate multiple jokes within a single input sequence.

2. **Hyperparameter Tuning:** Explored various hyperparameter combinations, setting values for batch size, epochs, learning rate, warmup steps, and maximum sequence length.

3. **Model Training:** Trained the GPT-2 model using the specified hyperparameters, saving model weights after each epoch for performance comparison.

4. **Joke Generation:** Used the trained model to generate jokes, selecting the best-performing version based on training epochs.

