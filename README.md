# Google AI Studio - Prototyping with Generative Models

Welcome to Google AI Studio, a browser-based Integrated Development Environment (IDE) for prototyping with generative models. This platform allows you to experiment with various generative models, create custom prompts, and fine-tune model parameters. When you're satisfied with your model, you can export the code for use in your own projects.

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Prototyping with Freeform Prompts](#prototyping-with-freeform-prompts)
4. [Prototyping with Structured Prompts](#prototyping-with-structured-prompts)
5. [Prototyping with Chat Prompts](#prototyping-with-chat-prompts)
6. [Exporting Models](#exporting-models)
7. [Further Resources](#further-resources)

## Introduction

Google AI Studio provides an intuitive interface for working with generative models. You can create and test different types of prompts and model configurations without writing any code. This readme will guide you through the process of creating prompts, adjusting model parameters, and exporting your models.

## Getting Started

1. **Accessing Google AI Studio:** Navigate to [Google AI Studio](https://geministudio.dev/) and log in with your Google account.

2. **Creating a New Project:** In the left panel, click on "Create new" and select the type of prompt you want to create.

3. **Exploring the Interface:** Familiarize yourself with the different sections of the interface, such as the prompt editor, model settings, and response viewer.

## Prototyping with Freeform Prompts

Freeform prompts allow you to create open-ended prompts for generating content or responses. You can use both images and text data for your prompts.

### Example:

```
look at the following picture and tell me who is the architect
```

1. **Creating a Freeform Prompt:** In the left panel, select "Create new" > "Freeform prompt."

2. **Adding an Image:** Click on the "Insert" button above the prompt area, select "Image," and choose an image.

3. **Running the Prompt:** Click on "Run" at the bottom of the app window to generate a response.

## Prototyping with Structured Prompts

Structured prompts combine instructions with examples to guide the model's output. This technique is useful for maintaining a consistent output format or when it's difficult to describe what you want the model to do in words.

### Example:

```
You are a product marketer targeting a Gen Z audience. Create exciting and fresh advertising copy for products and their simple description.
```

1. **Creating a Structured Prompt:** In the left panel, select "Create new" > "Structured prompt."

2. **Defining the Structure:** Under "Insert," add instructions for the structured prompt.

3. **Adding Examples:** Fill in example data for your structured prompt, including input and output examples.

4. **Testing the Prompt:** Use the "Test your prompt" table at the bottom to test your prompt with new input.

5. **Reviewing the Prompt:** Once you're satisfied, click on "Save" or "Get Code" to save or export your prompt.

## Prototyping with Chat Prompts

Chat prompts allow you to create conversational experiences. This technique is useful for building chatbots tailored to specific use cases.

### Example:

```
You are Tim, a friendly alien that lives on Europa, one of Jupiter's moons.
```

1. **Creating a Chat Prompt:** In the left panel, select "Create new" > "Chat prompt."

2. **Adding Examples:** Provide examples of interactions between a user and the chatbot.

3. **Testing the Chatbot:** Use the "Test your prompt" panel to test your chatbot's behavior.

4. **Customizing the Chatbot:** Add more examples and fine-tune your chatbot's responses.

5. **Exporting the Chatbot:** Once you're satisfied, click on "Get Code" to export your chatbot.

## Exporting Models

You can export your models to code in your preferred programming language. This allows you to use your models in your own projects.

1. **Saving the Prompt:** In the top right corner, click on "Save" to save your prompt.

2. **Exporting the Prompt as Code:** Click on "Get Code" to export your prompt as code. Choose the programming language you prefer and click "Copy" to copy the code to your clipboard.

## Further Resources

For more information on creating and fine-tuning prompts, refer to the [Google AI Studio Documentation](https://geministudio.dev/docs).

If you're ready to move on to coding with the exported models, check out the [API Quickstarts](https://geministudio.dev/docs/apis).
