# smart-chart-bot-
A list of PDF files is defined, each containing information related to nutrition and fitness.  The API returns a response in chunks, and each chunk is combined into a single string that represents the answer to the question. Finally, the answer is printed to the console.
Importing necessary libraries such as PyPDF2, re, nltk, TfidfVectorizer, cosine_similarity, and openai.
Setting up the OpenAI API key.
Defining a list of file names to be read.
Defining a function preprocess_text() to clean and preprocess the text.
Defining a function split_text() to split the text into passages of a fixed size.
Loading the contents of the PDF files using the PyPDF2 library.
Preprocessing the text.
Splitting the text into passages.
Setting up the OpenAI API request using the text-davinci-002 model.
Sending the request to the OpenAI API for each chunk of the prompt and storing the responses.
Combining the responses into a single string.
Printing the generated answer to the question "What is a healthy diet?" using the given passages from the PDF files.
