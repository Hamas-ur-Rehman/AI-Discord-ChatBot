# Discord AI Chatbot that Speaks like Your Favorite Character! and be your Companion and treat loneliness


This is a Discord AI Chatbot that uses the [Microsoft DialoGPT conversational model](https://huggingface.co/microsoft/DialoGPT-medium)


Here is a demo of the Discord bot in action.

<img src="https://github.com/Hamas-ur-Rehman/Hacktoberfest/blob/main/AI%20Discord%20ChatBot/resources/2gif2.gif?raw=true" width=500><br>

You can also directly chat with the model hosted on [Hugging Face's Model Hub](https://huggingface.co/Hamas/DialoGPT-large-jake2).

<img src="https://github.com/Hamas-ur-Rehman/Hacktoberfest/blob/main/AI%20Discord%20ChatBot/resources/1ezgif.com-gif-maker.gif?raw=true" width=400><br>

## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `chatbot.py`: Script to be imported into a Repl.it Python Discord.py project

## Inspiration
Loneliness can lead to various psychiatric disorders like depression, alcohol abuse, child abuse, sleep problems, personality disorders and Alzheimer's disease. This gave me the Idea why not create something that can think and talk like a human and help you feel good while talking to them. So there I created an AI chat bot that learns from your texts and adapts it into its own messages.


## What it does
The chat bot talks with the person with just a simple text. The chatbot uses the Microsoft DialoGPT conversational model. This is a fairly simple project targeting a large problem in health.

## How we built it
This chat bot uses the Microsoft DialoGPT conversational model. I also had to write custom dialogues for it to train over and work on. The chatbot's custom model is hosted using hugging face and the python file that helps link to discord is being hosted on Replit. The model training consumed about 1 whole day as its a small model therefore there wasn't much training needed. We can customize it to talk like your favorite character or person.

## Challenges we ran into
Writing dialogues to train the model on is a tedious and time consuming task and this was an issue I had to work on in order to get the project flowing.

## Accomplishments that we're proud of
I wasn't expecting the chatbot to pick up lines from the user's messages like Urdu words. This was some thing amazing and extraordinary for me and it further reassured me that it does learn.

# What we learned
From this project I learned the use of AI, Models, Hugging Face and how to use Discord bots.

# What's next for AI Chat Bot 
This is certainly not the end, few things I have planned for the AI chat companion :

- Making and Training on a larger dataset
- making it multi platform
- Currently you can talk to the chat bot on Hugging Face and Discord (select servers only) , but I plan to expand it to being able to SMS, use Facebook Messenger, WhatsApp, telegram and on twitter.
- Currently the chat bot only supports texts. I plan to implement chatting via voice as well and being able to have conversations on phone calls.
