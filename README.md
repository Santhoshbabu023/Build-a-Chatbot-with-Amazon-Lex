# Build-a-Chatbot-with-Amazon-Lex

## Overview

This project demonstrates the creation of a **Banking Chatbot** using **Amazon Lex**. The bot is designed to assist users with banking-related queries in a conversational and user-friendly manner. It supports both **text** and **voice** interactions, providing quick and efficient customer service.

## Features

- **WelcomeIntent**: Greets users when they first interact with the bot.
- **FallbackIntent**: Handles unrecognized inputs by prompting users to clarify or rephrase.
- **Response Variations**: Offers varied, conversational responses to improve user experience.
- **Text and Voice Support**: Interact with the bot through both text and voice channels.

## How it Works

1. **Creating Intents**: The bot responds to specific user inputs through defined intents like **WelcomeIntent** (for greetings).
2. **Handling Unrecognized Inputs**: The **FallbackIntent** is triggered when the bot doesn't recognize user input. It prompts the user to clarify or rephrase their message.
3. **Adding Variations**: Different variations are added to responses for a more natural conversation flow.
4. **Testing**: The bot was tested for both text and voice inputs to ensure seamless interactions.

## Setup

To deploy this project, follow these steps:

1. **Create an AWS Account**: If you don't have one, create an AWS account at https://aws.amazon.com/.
2. **Set Up Amazon Lex**:
   - Log in to the AWS Management Console.
   - Navigate to the **Amazon Lex** service.
   - Create a new chatbot using the provided configurations.
3. **Permissions**: Set up the necessary roles and permissions for the bot to function correctly.
4. **Create Intents**: Define the intents (such as **WelcomeIntent** and **FallbackIntent**) in the Amazon Lex console.
5. **Test the Bot**: Once set up, test the bot with sample inputs and ensure it responds correctly.

## Project Structure

- **Intents**: Configuration of chatbot intents for specific user interactions.
- **Variations**: A set of alternative responses to ensure natural conversation flow.
- **Testing**: Both text and voice-based testing for real-world interactions.

## Learnings

In this project, I learned how to:
- Define intents and configure chatbot responses in Amazon Lex.
- Use **FallbackIntent** to manage unrecognized inputs.
- Incorporate response variations for dynamic user interaction.
- Deploy and test a chatbot that supports both text and voice.

## Challenges

One of the unexpected challenges was refining the bot to handle diverse user inputs, especially with slang or informal language. Continuous training and testing were necessary to ensure accurate responses.

## Conclusion

This project showcases how **Amazon Lex** can be used to create conversational chatbots for automating customer service tasks. By leveraging **NLP** and **speech recognition**, the bot provides an efficient, user-friendly experience for banking-related queries.
