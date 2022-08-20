# Demonstration:

![image](https://user-images.githubusercontent.com/73461681/185761262-6a049b51-fdde-4497-bccf-8772730404ea.png)


# ChatBot Application:

* A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human. Chatbots are used a lot in 
customer interaction, marketing on social network sites and instantly messaging the client. There are two basic types of chatbot models based on how 
they are built, Retrieval based and Generative based models. Here, I have tried to implement a retrieval based machine learning model.

* A retrieval-based chatbot uses predefined input patterns and responses. It then uses some type of heuristic approach to select the appropriate response. 
It is widely used in the industry to make goal-oriented chatbots where we can customize the tone and flow of the chatbot to drive our customers with the 
best experience.


## Required Modules:
1) Python 3
2) nltk
3) Keras
4) pickle
5) NumPy
6) tkinter


# Contents of the Directory:

1) **Intents.json** – The data file which has predefined patterns and responses.
2) **train_chatbot.py** – In this Python file, we wrote a script to build the model and train our chatbot.
3) **Words.pkl** – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
4) **Classes.pkl** – The classes pickle file contains the list of categories.
5) **Chatbot_model.h5** – This is the trained model that contains information about the model and has weights of the neurons.
6) **Chatgui.py** – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.


## Setup Instructions
1) Clone the repository
```python
$ git clone https://github.com/rahulch02/Image-Classification-GUI.git
$ cd Image-Classification-GUI
```

2) Install the dependencies
  ##### For Python
  ```bash
  $ pip install -r requirements.txt
  ```


