# Text Analysis Tool

I was feeling bored, so I created this web page that allows you to analyze text. The page provides various statistics and information about the entered text, including:

- Number of words
- Number of characters
- Number of sentences
- Number of paragraphs
- Longest word
- Shortest word
- Average word length
- Word frequency

In addition, the page can also highlight pronouns in the text.

This tool was made with the help of AI using the GPT-3 language model.

## Live Demo

You can try out the text analysis tool by visiting the [live demo](https://master--text-analysis-tool.netlify.app/).

## How to Use

1. Enter the text you want to analyze in the "Enter your text" field.
2. Click the "Analyze Text" button.
3. The analysis results will appear below the button.

## How it Works

The page uses JavaScript to analyze the input text. The following functions are used for text analysis:

- `wordFrequency`: Calculates the frequency of each word in the text.
- `highlightPronouns`: Highlights pronouns in the text.
- `countWords`: Counts the number of words in the text.
- `countCharacters`: Counts the number of characters in the text.
- `countSentences`: Counts the number of sentences in the text.
- `countParagraphs`: Counts the number of paragraphs in the text.
- `findLongestWord`: Finds the longest word in the text.
- `findShortestWord`: Finds the shortest word in the text.
- `averageWordLength`: Calculates the average word length in the text.

Each function takes the input text as a parameter and returns the analyzed result.

The analysis results are displayed below the input field in an easy-to-read format. The word frequency is displayed as a JSON object. The page also highlights pronouns in the text using CSS.

Generated using the OpenAI API with the ChatGPT language model.

Enjoy analyzing your text!
