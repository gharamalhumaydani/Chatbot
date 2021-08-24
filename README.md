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

![2021-08-24 (21)](https://user-images.githubusercontent.com/86461558/130598732-bcd20bf0-c431-4a32-b4e8-ae79f8621817.png)


Create more than one list to save the data in which we will make a joint work.


![2021-08-24 (11)](https://user-images.githubusercontent.com/86461558/130598420-f17983fa-924b-4f81-a1c6-016a67bcbf4a.png)



Words :  We store all the words.

Labels : We store all the tags in it.

Docs_x : We store ordinary words.

Docs_y : We store the relationship between words and tag.



We use for loop
To add data to the list

![2021-08-24 (8)](https://user-images.githubusercontent.com/86461558/130598879-c9a11ba8-aa32-4946-8850-811759b0e483.png)



We will  stemmer the words in the word list, we will sort the words in the word list.



![2021-08-24 (9)](https://user-images.githubusercontent.com/86461558/130599126-b40b5312-2846-4776-8fd9-7edecabf2ac9.png)


We transform the list into a array for the model to understand.


![2021-08-24 (22)](https://user-images.githubusercontent.com/86461558/130601738-28631654-611f-418d-968e-4fde470fc0e4.png)

Create a new network that we are working to interact with,
Put the beginning of the model in it and save it.
 
 ![2021-08-24 (20)](https://user-images.githubusercontent.com/86461558/130599435-d0c38aab-b9a3-4396-aae6-b5c128f5f20a.png)
 
 We create a function to convert a user input into numbers that the model can understand.
 
 ![2021-08-24 (15)](https://user-images.githubusercontent.com/86461558/130599584-2dff769f-4eba-4df1-b95e-f60978ea50b0.png)

We are going to make another new function that we connect to model .

![2021-08-24 (17)](https://user-images.githubusercontent.com/86461558/130599670-67d1aa9d-d5ee-4f24-90a3-db2a3527eb21.png)





Result

When running the code in cmd using this Command (-python main.py)



![2021-08-24 (19)](https://user-images.githubusercontent.com/86461558/130599805-6f726dcd-7651-433f-850a-f5bc932e7006.png)



 
