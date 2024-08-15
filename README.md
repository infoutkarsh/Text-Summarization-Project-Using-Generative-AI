# Text Summarization Project using Generative AI

## Overview

This project demonstrates how to perform text summarization using generative AI models. It leverages the `facebook/bart-large-cnn` model from the Hugging Face `transformers` library to generate concise summaries from lengthy texts.

## Features

- **Generative AI**: Uses BART, a powerful model for abstractive summarization.
- **Flexible Configuration**: Adjust summary length and sampling options.

## Requirements

To run this project, you'll need:

- Python 3.6 or higher
- Libraries: `torch`, `transformers`, `numpy`, `scipy`, `tensorflow`

## Setup Instructions

1. **Clone the Repository**

   Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
   cd text_summarization_project
   ```

2. **Install Dependencies**

   Install the required libraries using `pip`. It's recommended to use a virtual environment for isolation:

   ```bash
   pip install -r requirements.txt
   ```

   Create a `requirements.txt` file with the following content:

   ```
   transformers
   torch
   numpy
   scipy
   tensorflow
   ```

## How to Use

1. **Prepare Your Input**

   Place the text you want to summarize in the `data/input.txt` file. 

2. **Run the Summarization Script**

   Execute the summarization script:

   ```bash
   python main.py
   ```

   The script will read the text from `data/input.txt`, generate a summary, and display it in the console.

3. **Customize Parameters**

   Modify the summarization parameters in the script if needed. You can adjust:

   - `max_length`: Maximum length of the summary
   - `min_length`: Minimum length of the summary
   - `do_sample`: Whether to use sampling for the summary

## Project Structure

```
text_summarization_project/
│
├── main.py                  # Main script for summarization
├── requirements.txt         # List of required libraries
├── README.md                # Project description and setup instructions
└── data/
    └── input.txt            # Input text file for summarization
```

## Contributing

Contributions are welcome! If you have improvements or suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions, reach out to 23mb0068@iitism.ac.in
