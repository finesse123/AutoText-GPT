# Next Word Prediction using NLTK

## Project Overview
This project focuses on building a **Next Word Prediction** model using **NLTK** and **machine learning techniques**. The model processes text data, constructs n-grams (bigrams and trigrams), and predicts the most probable next word based on context.

## Features
- Tokenizes sentences into words
- Generates bigrams and trigrams
- Predicts the next word using probability distributions
- Implements machine learning techniques for text prediction

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install nltk numpy pandas
```

## Step-by-Step Process

### 1. Basic Setup
- Import necessary libraries such as `nltk`, `numpy`, and `pandas`.
- Load the dataset containing textual data.

### 2. Loading the Dataset
- The dataset is structured as a list of sentences, where each sentence is a list of words.

### 3. Creating N-grams
- Generate **unigrams, bigrams, and trigrams** from the dataset.
  
  Example:
  - **Sentence**: "This is a Data Science Course"
  - **Bigrams**: "This is", "is a", "a Data", "Data Science", "Science Course"
  - **Trigrams**: "This is a", "is a Data", "a Data Science", "Data Science Course"

### 4. Building the Prediction Model
- Use probability distributions to analyze n-grams and predict the most likely next word.

### 5. Model Evaluation
- Evaluate the model based on accuracy, perplexity, and fluency.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd Next-Word-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Next_Word_Prediction.ipynb
   ```

## Future Enhancements
- Integrate **Transformers** (e.g., GPT-2) for more advanced predictions.
- Implement **GPTTokenizer** for better text preprocessing.
- Improve accuracy using deep learning techniques.

## Contributing
Feel free to fork this repository and improve the model. Contributions are welcome!

## License
This project is licensed under the MIT License.

