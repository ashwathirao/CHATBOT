# CHATBOT

The chatbots can be used in medical field, casual companion, discussion solver based on the dataset on which the model is being trained.​
Replaces human work in the multiple fields like customer service, medicine suggestion, etc,.​
It acts as a virtual human messenger.​
This is intended to give most exact answers as it is retrived from patterns and responses, hence can be well used in medical field.

The dataset we use is stored as ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user. ​
Intents.json – The data file which has predefined patterns and responses. Predefined dataset.​
train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.​
Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.​
Classes.pkl – The classes pickle file contains the list of categories.​
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.​
Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.​
