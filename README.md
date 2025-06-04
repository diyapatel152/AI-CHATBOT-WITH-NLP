# AI-CHATBOT-WITH-NLP

COMPANY: CODETECH IT SOLUTIONS

NAME: PATEL DIYA 

INTERN ID :CT04DF1541

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

## TASK DESCRIOTON:

This project is a simple yet powerful NLP-based chatbot built using Python. It is designed to simulate human-like conversation and assist users with a variety of tasks including greetings, jokes, basic knowledge responses, and arithmetic calculations such as addition, subtraction, multiplication, and division. The chatbot is implemented in a Jupyter Notebook environment, making it accessible and beginner-friendly for students, developers, or anyone exploring Natural Language Processing (NLP) and machine learning applications. It leverages NLTK (Natural Language Toolkit) for text preprocessing and classification, and includes a customizable intents dictionary to define various topics the chatbot can handle.

**Project Overview**
The chatbot uses a predefined set of intents and patterns to recognize user queries and respond appropriately. The project is based on a lightweight NLP approach that includes tokenization, lemmatization, and vectorization using TfidfVectorizer. It then applies a simple machine learning model (LogisticRegression) to classify input sentences into categories (or intents). Each intent contains a "tag", multiple "patterns" (ways a user might ask something), and a list of "responses" that the bot can randomly choose from. For mathematical queries, such as addition or division, the bot extracts numbers from the sentence and performs calculations dynamically.

**Features**
- Conversational Intent Recognition: Using pattern matching and classification,the chatbot can identify the user's intent from text input and react accordingly. Greetings,good-byes,appreciation,assistance,and jokes are among the intentions.
- Extendable Intents: Developers can easily extend the chatbot by adding new intents, patterns, and responses in the intents dictionary. This modularity makes it perfect for learning and experimentation.
- Interactive Chat Interface: Use an improved GUI with ipywidgets or a terminal-style loop to communicate.
- Simple Customization: By adding more intents and dictionary-formatted responses, you can quickly expand the chatbot.

**Technologies Used**
- Python 3
- NLTK (Natural Language Toolkit)
- Jupyter Notebook (for interactive development)

**How to Use**
1. Clone the repository or download the .ipynb file.
2. Open it with Jupyter Notebook or JupyterLab.
3. Run all the cells sequentially to load the model and start the chat.
4. Type messages like “Hi”, or “Tell me a joke”.
5. Type “quit” to exit the chat.




