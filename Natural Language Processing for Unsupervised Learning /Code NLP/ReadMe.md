# What is this project about and what did I do  ?
The goal of this project is to apply NLP techniques to a text from Wikipedia that I scraped using BeautifulSoup. This text is about Obi-Wan Kenobi from Star Wars. Throughout this project, I utilized Spacy, a Python library and toolkit designed for efficient text data processing.

As the text is in French, I configured Spacy to work with the French language. To apply NLP techniques:

I removed punctuation marks, converted the text to lowercase, and merged sentences containing spaces to create a homogeneous document.
I trained an NLP model on this cleaned document.
Following that, I removed stop words and updated the stop words list to include repeated words that do not contribute meaningful information to the document.
I employed the word cloud technique to visualize the most important words in the document.
Additionally, I used the TF-IDF matrix to assess the importance of each word within the document.
Do not hesitate to have a look on the code to understand more !
