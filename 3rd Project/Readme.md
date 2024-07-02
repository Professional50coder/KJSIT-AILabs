
# Book Recommendation System with CNN

This project implements a book recommendation system using a Convolutional Neural Network (CNN) model. The system allows users to search for books based on keywords and displays relevant book information.

## Features

- Loads and preprocesses book data from a CSV file
- Provides functions to search for books based on keywords
- Displays book details such as title, author, average rating, ISBN, language, number of pages, ratings count, text reviews count, publication date, and publisher
- Utilizes a CNN model for image classification (using the CIFAR-10 dataset) as a proof of concept

## Prerequisites

- Python 3.x
- Required libraries: `pandas`, `tensorflow`, `keras`, `numpy`, `matplotlib`

## Installation

1. Clone the repository or download the source code.
2. Install the required libraries using pip:

```bash
pip install pandas tensorflow keras numpy matplotlib
```

3. Ensure that the `books.csv` file containing the book data is located in the specified path (`'/content/drive/My Drive/Colab Notebooks/books.csv'`).

## Usage

1. Run the Jupyter/Colab Notebook file `Book_rec_system_with_CNN.ipynb`.
2. The notebook will mount Google Drive and load the book data from the CSV file.
3. Enter a keyword in the input prompt to search for books.
4. The system will display the search results, including book titles, authors, average ratings, ISBNs, languages, number of pages, ratings count, text reviews count, publication dates, and publishers.
5. The notebook also includes code to train and evaluate a CNN model using the CIFAR-10 dataset, which is not directly related to the book recommendation system but serves as a proof of concept for using CNN models.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
