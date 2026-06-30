# AI Text Generator using GPT-2

## Overview

This project is a simple AI-powered text generation application built using the Hugging Face Transformers library. It loads the GPT-2 language model and generates human-like text based on a user-provided prompt.

The application runs locally and demonstrates how to use pre-trained Large Language Models (LLMs) for text generation.

---

## Features

- Generate AI-powered text from any prompt
- Uses the pre-trained GPT-2 model
- Interactive command-line interface
- Easy to understand and modify
- Beginner-friendly project

---

## Technologies Used

- Python 3.x
- Hugging Face Transformers
- PyTorch

---

## Project Structure

```
AI-Text-Generator/
│
├── app.py              # Main Python file
├── requirements.txt    # Required libraries
├── README.md           # Project documentation
```

---

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/AI-Text-Generator.git
```

### Step 2: Navigate to the project

```bash
cd AI-Text-Generator
```

### Step 3: Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install transformers torch
```

---

## How to Run

Run the Python file:

```bash
python app.py
```

---

## Example

Input:

```
Enter your prompt:
Artificial Intelligence is
```

Output:

```
Artificial Intelligence is transforming industries by enabling machines
to learn from data and perform tasks that normally require human intelligence...
```

---

## Code Explanation

The program performs the following steps:

1. Imports the Transformers pipeline.
2. Loads the GPT-2 model.
3. Accepts user input.
4. Sends the prompt to the model.
5. Generates AI text.
6. Displays the generated output.

---

## Parameters Used

| Parameter | Description |
|-----------|-------------|
| max_length | Maximum number of tokens generated |
| temperature | Controls creativity of the output |
| top_k | Limits token selection to the top K choices |
| top_p | Uses nucleus sampling for better generation |
| do_sample | Enables random sampling |
| num_return_sequences | Number of generated outputs |

---

## Requirements

- Python 3.8 or above
- Transformers
- Torch

Install using:

```bash
pip install transformers torch
```

---

## Future Improvements

- Use larger language models
- Add a graphical user interface
- Build a web application using Flask or Streamlit
- Save generated responses to a file
- Support chat-based conversations
- Add customizable generation settings

---

## Author

**Yuvashree E**

---

## License

This project is intended for educational and learning purposes.
