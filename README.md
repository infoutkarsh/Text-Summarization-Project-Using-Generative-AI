# Text Summarization Project Using Generative AI

## Overview

This project focuses on implementing text summarization using advanced generative AI techniques. By leveraging the `facebook/bart-large-cnn` model from the Hugging Face `transformers` library, this project transforms lengthy texts into concise, meaningful summaries, making it easier to extract key information from large volumes of data.

## Key Features

- **Generative AI Capabilities**: I utilized BART, a state-of-the-art model for performing **abstractive summarization**, which generates summaries that capture the essence of the input text rather than merely extracting sentences.
- **Customizable Summarization**: I implemented flexibility in configuring the length and style of the summary, allowing users to tailor the output to their specific needs.
- **Scalable and Efficient**: The project was designed to handle various text lengths, from short paragraphs to long documents, with adjustable parameters to optimize performance.

## Requirements

The following Python libraries were required:

- **torch** for handling model computations.
- **transformers** for leveraging pre-trained generative models.
- **numpy** for numerical operations.
- **scipy** for scientific computing.
- **tensorflow** for additional deep learning capabilities.

## Setup Instructions

### 1. Install Dependencies

To set up the environment, I used `pip` to install the necessary libraries. I recommend using a virtual environment to keep the dependencies isolated from other projects:

```bash
pip install -r requirements.txt
```

I created a `requirements.txt` file containing the following:

```
transformers
torch
numpy
scipy
tensorflow
```

### 2. Input Data

I placed the text for summarization in a dedicated file located at `data/input.txt`. This approach simplifies input management and ensures that the script processes the correct content.

### 3. Execute the Summarization Script

I created a script (`main.py`) to automate the summarization process. Running the script generates a summary of the text in `data/input.txt`:

```bash
python main.py
```

The output summary is displayed in the console, providing immediate feedback on the text processing.

### 4. Adjust Summarization Parameters

During development, I incorporated adjustable parameters within the script to control the summarization output:

- **`max_length`**: Defines the maximum number of tokens in the summary.
- **`min_length`**: Sets the minimum number of tokens to ensure completeness.
- **`do_sample`**: Enables or disables sampling, allowing for more varied summaries when enabled.

These parameters were crucial in fine-tuning the summaries to meet specific requirements.

## Project Structure

The project is structured to maintain clarity and ease of use:

```
text_summarization_project/
│
├── main.py                  # Core script automating the summarization process
├── requirements.txt         # List of required libraries for the project
├── README.md                # Detailed project description and setup instructions
└── data/
    └── input.txt            # Input text file for summarization
```

## Contact

For any queries, feedback, or collaboration opportunities, you can reach me at [23mb0068@iitism.ac.in](mailto:23mb0068@iitism.ac.in).
