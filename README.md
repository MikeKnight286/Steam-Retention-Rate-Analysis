# Predicting Player Retention Rate of a Steam Game Based on its Reviews

## Author

- **Name:** Bhone Tay Zar Kyaw

## Overview

This project aims to predict the player retention rate for Steam games by analyzing game reviews. The approach involves text analysis and machine learning models to understand how player feedback correlates with their likelihood to continue playing a game. This analysis could provide valuable insights for game developers and marketers to improve player engagement and retention strategies.

## Installation

To run the project, you will need to install several dependencies and download necessary resources for neural network visualization and text processing.

### Dependencies Installation

1. **Graphviz for Neural Network Visualization:**
   - On macOS, use Homebrew:
     ```shell
     brew install graphviz
     ```
   - Then, install Python packages:
     ```shell
     pip install pydot pydotplus
     ```

2. **GloVe Embeddings for Text Preprocessing:**
   - Download GloVe embeddings from the following link:
     [GloVe Twitter Embeddings](https://huggingface.co/stanfordnlp/glove/resolve/main/glove.twitter.27B.zip)

3. **Additional Python Packages:**
   - Ensure you have other necessary Python packages installed. While the exact list is not provided here, typical data science packages include `numpy`, `pandas`, `matplotlib`, `scikit-learn`, and `tensorflow` or `pytorch` for neural network models.

### GitHub Resources

- For text preprocessing, visit the following GitHub repository for guidance and tools:
  [StanfordNLP GloVe GitHub](https://github.com/stanfordnlp/GloVe)

## How to Use

1. **Prepare the Data:**
   - Download and preprocess the Steam game reviews using the provided scripts. Ensure the GloVe embeddings are correctly placed in your project directory.

2. **Model Training:**
   - Utilize the provided Jupyter notebook to train the machine learning models. The notebook includes detailed steps for data preprocessing, model setup, training, and evaluation.

3. **Evaluation and Prediction:**
   - Evaluate the model's performance using the metrics outlined in the notebook. Use the trained model to predict the retention rate based on new reviews.

## Contributing

If you're interested in contributing to this project, please fork the repository and submit a pull request with your proposed changes. Feedback and improvements are always welcome.

