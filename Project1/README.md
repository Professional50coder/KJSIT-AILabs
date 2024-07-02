# Sentiment Analysis on Customer Feedback

This project performs sentiment analysis on customer feedback using the VADER (Valence Aware Dictionary and sEntiment Reasoner) and TextBlob libraries in Python. The analysis is presented through a Streamlit web application.

## Features

1. **Load and preprocess customer feedback data** from a CSV file.
2. **Analyze sentiment and subjectivity** using VADER and TextBlob.
3. **Classify sentiment** based on VADER scores into categories: highly positive, positive, neutral, negative, and highly negative.
4. **Provide a user interface** using Streamlit to input customer feedback and display sentiment analysis results.
5. **Clean and display text** entered by the user.
6. **Generate a histogram** to visualize the distribution of sentiment scores by class.
7. **Display a DataFrame** with sentiment analysis results, including sentiment class, sentiment score, and subjectivity.

## Snapshorts of the Model 
![Screenshot 2024-07-01 225117](https://github.com/Professional50coder/KJSIT-AILabs/assets/135821867/f28ca7cf-d9df-4541-b0df-fecb00a17017)
![Screenshot 2024-07-01 225154](https://github.com/Professional50coder/KJSIT-AILabs/assets/135821867/35f278c0-8597-483c-8e5a-caeb45869ac0)
![Screenshot 2024-07-01 225228](https://github.com/Professional50coder/KJSIT-AILabs/assets/135821867/9f188086-c0d1-4e4c-9853-25b3c179f951)

## Prerequisites

- Python 3.x
- Required libraries: `streamlit`, `textblob`, `pandas`, `vaderSentiment`, `cleantext`, `matplotlib`

## Installation

1. Clone the repository or download the source code.
2. Install the required libraries using pip:

```bash
pip install streamlit textblob pandas vaderSentiment cleantext matplotlib
```

3. Ensure that the `Reviews.csv` file containing the customer feedback data is located in the specified path .

## Usage

1. Run the Streamlit app from the command line:

```bash
streamlit run app.py
```

2. The Streamlit app will open in your default web browser.
3. Enter customer feedback in the text area provided.
4. The app will display the sentiment analysis results, including VADER sentiment class, VADER sentiment scores, TextBlob polarity, and TextBlob subjectivity.
5. You can also enter text in the "Clean Text" input field to see the cleaned version of the text.
6. The histogram will show the distribution of sentiment scores by class.
7. The DataFrame will display the sentiment analysis results for the first 30 rows of the input data.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
