# Code Similarity Detection Using Fuzzy Logic

## Overview
This project implements a system to detect similarity between source code snippets using Abstract Syntax Tree (AST) analysis and textual comparison. A fuzzy logic model integrates these metrics to produce an overall similarity score, assisting in assessing originality and preventing copyright infringement.

## Features
- **AST Analysis**: Analyzes the structure of code snippets to determine similarity.
- **Textual Similarity**: Computes the textual similarity percentage between code strings.
- **Fuzzy Logic Model**: Utilizes fuzzy logic to evaluate overall similarity based on AST and textual metrics.
- **Similarity Classification**: Categorizes similarity scores into distinct classes.

## Requirements
- Python 3.x
- `numpy`
- `skfuzzy`

## Usage
1. Import the necessary libraries.
2. Define the code snippets you want to compare.
3. Call the `compare_codes(code1, code2)` function to get the similarity score and classification.

## Functionality
- `analyze_ast(code):` Analyzes the AST of the given code.
- `calculate_text_similarity(code1, code2):` Computes the textual similarity percentage.
- `create_fuzzy_logic_model():` Creates and configures the fuzzy logic model.
- `compare_codes(code1, code2):` Main function to compare two code snippets.
- `classify_similarity(score):` Classifies the similarity score into categories.

## Acknowledgments
- Skfuzzy for fuzzy logic implementation.
- Numpy for numerical operations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
