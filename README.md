# QA_paragraph_ML-model-
Question Answering ML model .. which analyse the given input paragraph and gives accurate answer to user given question..This projects used pretrained models from Transformers in Huggingface 
1. Project Overview 

This project showcases the implementation of an extractive question-answering system leveraging the Hugging Face Transformers library and a pretrained BERT model fine-tuned for SQuAD-style tasks. Users can input a context passage and pose natural-language questions; the system extracts the best answer span directly from the context.

2. Objectives

Demonstrate the capabilities of BERT in extracting answers from contextual text.

Provide a Python-based demo for learners and developers to get started with QA systems.

Highlight key differences between extractive and generative question answering approaches.
3. Technical Components
Library & Model

Utilizes the transformers library by Hugging Face — the go-to toolkit for transformer-based architectures such as BERT, RoBERTa, DistilBERT, etc. 
Wikipedia

Employs a pretrained, fine-tuned BERT model (e.g., bert-large-uncased-whole-word-masking-finetuned-squad) tailored for extractive QA tasks such as SQuAD

Workflow

Input: A context paragraph and a natural-language question.

Processing: Tokenizer encodes the inputs; BERT predicts start and end positions of the answer text within the context.

Output: The extracted answer span, along with confidence scores and token indices. Typical demo outputs include answer text like "12,103.6 km" (e.g., “What is the diameter of Venus?”) with associated confidence.
