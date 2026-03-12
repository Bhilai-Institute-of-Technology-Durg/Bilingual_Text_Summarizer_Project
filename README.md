Bilingual Text Summarizer project uses BART-Large for abstractive summaries in English and Hindi with multiple flexible modes.

# Bilingual Abstractive Text Summarizer using BART-Large

## 1. Introduction

Text summarization is an important task in Natural Language Processing (NLP) that helps convert long pieces of text into shorter summaries while preserving the main meaning. This project implements an interactive abstractive text summarization system using the BART-Large deep learning model. The system is capable of generating human-like summaries and supports bilingual functionality by allowing both English and Hindi input and output.

## 2. Objective

The main objectives of this project are:

* To design an automatic text summarization system.
* To generate meaningful summaries from long text documents.
* To support bilingual text summarization in English and Hindi.
* To demonstrate the use of deep learning models in NLP applications.

## 3. Problem Statement

Reading long documents or articles can be time-consuming. Users often need a quick overview of the important information. This project solves the problem by automatically generating a short summary from a long text while maintaining the essential meaning.

## 4. Technologies Used

The following technologies and tools are used in this project:

* Python Programming Language
* Natural Language Processing (NLP)
* HuggingFace Transformers Library
* BART-Large Model (facebook/bart-large-cnn)
* PyTorch
* NLTK (Natural Language Toolkit)
* Google Translate API (googletrans)
* TQDM for progress display

## 5. Project Features

This text summarization system provides several useful features:

* Interactive command-line interface
* Single text summarization
* Paragraph-wise summarization
* Long document summarization using chunking
* Structured multi-paragraph summaries
* Automatic language detection
* Support for English and Hindi input/output
* Display of summary statistics and execution time

## 6. Project Structure

The project folder is organized as follows:

Bilingual_Text_Summarizer_Project/

interactive_summarizer.py
summarizer.py
requirements.txt
README.md
input.txt

screenshots/
  output1.png
  output2.png

presentation/
  project_presentation.pptx

## 7. Installation

To run the project, install the required libraries using the following command:

pip install -r requirements.txt

The required libraries include:

* torch
* transformers
* nltk
* tqdm
* googletrans==4.0.0rc1

## 8. How to Run the Project

Follow these steps to run the project:

1. Download or clone the project folder.
2. Open the project folder in the terminal or command prompt.
3. Install the required libraries.
4. Run the main program using the command below.

python interactive_summarizer.py

5. Enter the text manually or load a text file.
6. Choose the language options and summarization mode.
7. The program will generate the summary and display the results.

## 9. Working of the System

The working process of the system is as follows:

1. The user provides input text manually or through a file.
2. The system detects the language of the input text.
3. If the input text is in Hindi, it is translated into English.
4. The BART-Large model processes the text and generates an abstractive summary.
5. If the user selects Hindi output, the summary is translated back into Hindi.
6. The system displays the final summary along with processing statistics.

## 10. Output

The system produces the following output:

* Generated summary
* Execution time
* Number of words and sentences
* Percentage reduction of text
* Original input text for comparison

## 11. Conclusion

This project successfully demonstrates the implementation of an abstractive text summarization system using deep learning techniques. By using the BART-Large model, the system is able to produce high-quality summaries that retain the key information from the original text. The bilingual feature further enhances usability by allowing users to work with both English and Hindi text.

## 12. Future Scope

The project can be further improved with the following enhancements:

* Development of a graphical user interface (GUI)
* Support for additional languages
* Integration with web applications
* Improved translation accuracy
* Deployment as a cloud-based summarization service

## 13. References

1. HuggingFace Transformers Documentation
2. BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation
3. NLTK Official Documentation
4. Google Translate API Documentation
