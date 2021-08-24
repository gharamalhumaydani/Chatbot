# Creating-chatbot-model

In this project I created a chatbot using python.

Data

Start by creating a Json file which will holds the chatbot intents, you can create it by opening any text editor paste your code and save that file with the .json extension.

This file contains the intents for the chatbot to recognize and respond correctly to the user as it has samples of what the user would say (patterns) and what's the correct respond (responses)

![2021-08-24 (4)](https://user-images.githubusercontent.com/86461558/130567924-40a751d3-72f2-435b-85ca-3bb49cbbf998.png)


Each conversational intent contains:

a tag (a unique name)

patterns (sentence patterns for our neural network text classifier)

responses (one will be used as a response)



Download the libraries we need.

![2021-08-24 (2)](https://user-images.githubusercontent.com/86461558/130568083-08243b60-d1d9-4bb8-a4bd-203bd77a123a.png)

We open our data file and upload it to a file
my own script.

![2021-08-24 (6)](https://user-images.githubusercontent.com/86461558/130578081-d636d2a6-2335-4136-a30c-eb9a02cfd205.png)



Create more than one list to save the data in which we will make a joint work

Words :  We store all the words.

Labels : We store all the tags in it.

Docs_x : We store ordinary words.

Docs_y : We store the relationship between words and tag.


 
 
 
