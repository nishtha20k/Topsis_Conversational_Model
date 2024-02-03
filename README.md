## Overview
The objective of this project is to assess the performance of various language models in generating responses to predefined prompts. The evaluation criteria include ROUGE scores and response length. Additionally, the project utilizes TOPSIS analysis to rank the models.<br />

## Project Structure
**Script**: The main script i.e Topsis_Pre_Trained.ipynb encompasses the code for evaluating language models .<br />

**Results**: The results of the script are stored in :- 
- results.csv : A detailed CSV file containing the results of the evaluation.
- topsis.csv  : A CSV file containing the outcomes of the TOPSIS analysis.

**Graphs:** Bar graphs comparing TOPSIS scores and individual metrics (ROUGE-1, ROUGE-2, ROUGE-L, and Response Length) are saved as PNG files.<br />

## Dependencies
- *torch*: PyTorch library for deep learning.<br />
- *transformers*: Hugging Face Transformers library for pre-trained language models.<br />
- *nltk*: Natural Language Toolkit for BLEU score calculation.<br />
- *rouge-score*: Library for ROUGE score calculation.<br />
- *pandas*: Data manipulation library.<br />
- *matplotlib*: Plotting library.<br />
- *numpy*: Numerical computing library.<br />
