# C Programming Question Paper Generator using RAG

This repository implements a **C Programming Question Paper Generator** using **Retrieval-Augmented Generation (RAG)**. The goal is to generate high-quality C programming questions with accurate answers by combining retrieval-based models with generative capabilities.

## Features
- Automatically generate C programming questions.
- Incorporates RAG for improved accuracy and relevance of generated questions.
- Covers various difficulty levels: Beginner, Intermediate, Advanced.
- Ability to retrieve existing question patterns and augment them with generative models.
- Supports custom input and dataset for specific question generation.

## Technologies Used
- **RAG Model:** Combines retrieval and generation to create relevant questions.
- **LangChain:** Framework to streamline the use of LLMs with retrieval mechanisms.
- **Python:** Backend logic and RAG model integration.
- **C Programming Knowledge Base:** Custom dataset of C programming questions and answers.

## How It Works
1. **Data Retrieval:** The system first retrieves similar questions from a predefined C programming question bank.
2. **Generation:** The generative model augments the retrieved information to create unique questions.
3. **Output:** The generated questions are presented in a structured format, ready for use in exams or quizzes.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/C-Programming-Question-Generator.git
    cd C-Programming-Question-Generator
    ```

2. Set up the Python environment:
    ```bash
    conda create -n c-question-gen python=3.9
    conda activate c-question-gen
    pip install -r requirements.txt
    ```

3. Download the required models:
    - Make sure you have access to the RAG model and install the necessary dependencies.

## Usage
1. Run the script to generate C programming questions:
    ```bash
    python generate_questions.py
    ```

2. Provide input to customize the question generation based on specific topics or difficulty levels.

## Configuration
- **Dataset:** You can customize the dataset by modifying the `questions_dataset.csv`.
- **Model Parameters:** Adjust the retrieval and generation settings in `config.yaml`.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.

