# CHATBOT

## Introduction
An artificial intelligence labeled a chatbot imitates a conversation with a user through chat or apps.

- Chatbots are the future of AI, as they provide the closest to a natural conversation between humans and machines. Chatbots are not new to us; the first chatbot was Eliza, but it was not as complex as the chatbots we have nowadays, such as Siri or Alexa.

- Due to the new ML and AI techniques, chatbots are expected to complete 90\% of our tasks in the future, but there is still a long way to go. The progress we have made with chatbots thus far is, nonetheless, astonishing.

## Features
- In this activity, we will be used a Python library, chatterbot, to implement a chatbot.
- This library generates automated responses to the user input. The responses are based on machine learning algorithms implemented in the library.
- Our goal is to make sure that the chatbot is trained in multiple languages in order to cater to different communities.
- The ML algorithms make it easier for the chatbot to improve and evolve its responses over time as it collects user responses.
- These features make it easier for the chatbot to engage in conversations through different mobile apps and websites. It saves input data from the user and evolves over time. The accuracy of the chatbot response increases over time as it learns from the user.

## Limitations
Sometimes it can become difficult to work with the chatbot, and we have to set our expectations accordingly.

## Domain knowledge
A chatbot is a machine, and it has specific domain knowledge. We cannot expect the chatbot to know everything about everything. We are far from the AI we see in movies, so we need to have realistic expectations while designing a chatbot.

## Conversation boundaries
Because it cannot understand what you are saying, a chatbot may at first give you an erroneous answer to your inquiries. Although this could be annoying at times, we must keep in mind that we are interacting with a computer and not a real person.

## Personality
A conversation with a computer is very different from a conversation with another human. We may expect the chatbot to have the following distinguishable human traits:

- Empathy
- Emotions
- Intelligence
We are far away from reaching a level of communication with AI that is indistinguishable from human communication, but we may achieve this sometime in the future.

# Explanation
- After checking for the identity of the user in line 10, we have written rules and facts for responding to the different identities.
- If the identity is **Mark**, we skip all the cases below and go straight to line 23. Otherwise, we check if the identity is **Jane**.
- If the identity is unknown, we respond accordingly and exit the program using the **exit()** command.
- Once the identity is confirmed as **Mark** or **Jane**, the program skips to line 24, and the code below is executed.
- In line 32, we check whether the identity is **Mark** before we train the bot with **Mark’s** personal information. Otherwise, code jumps to line 51 and starts the bot.
- If the identity is **Mark**, we add our custom data in the form of lists from lines 33-51. The first object of the list is the question, and the second object of the list is the answer.
- Once we have added all of our new data, we train the bot with the custom data using the **custom_train()** function from lines 53-56. The bot will not learn the answers to the questions by simply adding the custom data in the code. We will need to explicitly train the bot with all the custom data.
- After training the bot with our custom data, we start the bot using the **start_chatbot()** function.
