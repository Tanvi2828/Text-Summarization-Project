# Text-Summarization Project
This is an **Text Summarization Tool** built in Python that takes a block of text and summarizes it by extracting the most important sentences. It leverages a simple algorithm that uses word frequencies and excludes common stopwords to calculate the significance of sentences in the text. 

### Key Features:
- **Text Preprocessing**: Removes special characters, extra spaces, and converts the text to lowercase.
- **Stopwords Removal**: Excludes common English words (e.g., "the", "and", "is") from word frequency calculations.
- **Sentence Scoring**: Scores sentences based on the frequency of significant words.
- **Summary Generation**: Generates a summary by selecting the most important sentences.

### Technologies Used:
- **Python**: The core logic for text processing, summarization, and user interface.
- **Regular Expressions**: For cleaning the text and removing unwanted characters.
- **Collections Module**: To calculate word frequencies using the `Counter` class.

### How It Works:
1. **Preprocessing**: The input text is cleaned by removing special characters and converting it to lowercase.
2. **Word Frequency Calculation**: A frequency count of the remaining words (after removing stopwords) is generated.
3. **Sentence Scoring**: Each sentence in the text is scored based on the frequency of its words. Sentences with higher scores are deemed more important.
4. **Summary Generation**: The sentences with the highest scores are selected to form the summary.

### How to Use:
1. Clone or download the repository to your local machine.
2. Ensure you have Python installed (Python 3.x recommended).
3. Run the script using the following command:
    ```bash
    python summarizer.py
    ```
4. You will be prompted to input the text you want to summarize and specify how many sentences you would like the summary to contain.
5. The tool will output the summary based on the most significant sentences from the input text.

### Example:
```plaintext
Enter the text to summarize:
Natural language processing (NLP) is a branch of artificial intelligence (AI) that helps computers understand, interpret, and generate human language. NLP involves several tasks, such as language translation, sentiment analysis, and text summarization. It uses machine learning algorithms to process text data and generate meaningful insights. The goal of NLP is to enable machines to communicate with humans in a way that feels natural.

Enter the number of sentences for the summary: 2

Summary:
NLP involves several tasks, such as language translation, sentiment analysis, and text summarization. The goal of NLP is to enable machines to communicate with humans in a way that feels natural.
```

### Installation:
1. Clone the repository:
    ```bash
    git clone https://github.com/Tanvi2828/Text-Summarization-Project
    ```
2. Navigate to the project directory:
    ```bash
    cd text-summarization-tool
    ```
3. Install necessary dependencies (if any):
    ```bash
    pip install -r requirements.txt
    ```

### Future Enhancements:
- **Advanced Summarization Algorithms**: Implement machine learning-based summarization techniques (e.g., extractive or abstractive summarization).
- **Support for Multiple Languages**: Add support for summarizing text in different languages.
- **User Interface (UI)**: Create a GUI version of the tool for easier use.

### Acknowledgments:
- This tool is built using basic Python libraries and algorithms. Special thanks to the open-source community for their contributions to Python’s libraries.


