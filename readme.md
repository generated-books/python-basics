# Python Basics: An AI-Generated Jupyter Book

This repository contains an AI-generated Jupyter Book on Python basics. The book covers fundamental Python concepts and progresses to more advanced topics in data analysis and machine learning.

## About This Book

This entire book, including all notebooks and content, is AI-generated. The process of creation and the code used to generate this book can be found in the [`generator.ipynb`](generator.ipynb) file in this repository.

## Building the Book

To build the book locally, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/generated-books/python-basics.git
   cd python-basics
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r docs/requirements.txt
   ```

4. Build the book:
   ```
   jupyter-book build docs/
   ```

5. The built book will be in the `docs/_build/html/` directory. You can open the `index.html` file in your web browser to view the book.

## Viewing the Book Online

This book is also hosted online using GitHub Pages. You can view it at: https://generated-books.github.io/python-basics/

## Contributing

As this is an AI-generated book, we are not currently accepting direct contributions. However, if you notice any issues or have suggestions for improvements, please feel free to open an issue in this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.