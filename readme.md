# Azure OpenAI C# Prompt Engineering Samples

 This project is a port of the [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/chatgpt-prompt-eng) samples from OpenAI / Python to C# / Azure-OpenAI. It uses [Interactive Notebooks for C#](https://github.com/dotnet/csharp-notebooks), [Azure OpenAI service](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/ai.openai-readme?view=azure-dotnet-preview), and the [Azure OpenAI client library for .NET](https://www.nuget.org/packages/Azure.AI.OpenAI).

## Prerequisites

1. Clone this repo locally
2. In Azure, create **Azure OpenAI Service** resource. After deploying the model, note the model name, you'll need it for the **AOAI_DEPLOYMENTID** environment variable below.
3. Install the **Polyglot Notebooks** extension in Visual Studio Code.
2. Configure environment variables

    For more details on how to get these variables, see the [Azure OpenAI documentation](https://learn.microsoft.com/azure/cognitive-services/openai/quickstart?tabs=command-line&pivots=programming-language-csharp#retrieve-key-and-endpoint).


    Create the following environment variables:

    **AOAI_ENDPOINT** - The endpoint for your Azure OpenAI Service resource.

    **AOAI_KEY** - The access key for your Azure OpenAI Service resource.

    **AOAI_DEPLOYMENTID** - The name of your model deployment (e.g. my-davinci-003-deployment)

## Running the Notebooks

Open a Jupyter Notebook file (links below) in VS Code. You can run and change the code.

## Prompt Types

[**Iterative**](./PE-Iterative.ipynb): Modifying the prompt until it gives you the correct output

[**Summarizing**](PE-Summarizing.ipynb): Providing summarized output

[**Inferring**](./PE-Inferring.ipynb): Sentiment Analysis, Emotion detection, Entity Extraction

[**Transforming**](./PE-Transforming.ipynb): Language translation and detecting

[**Expanding**](./PE-Expanding.ipynb): Generate text based on tone and sentiment of input

[**Chatbot**](./PE-ChatBot.ipynb): Chat using system, user, and assistant message roles.

[**Orderbot**](./PE-Order.ipynb): Interactive chat using turn-based input to add to context

## References

https://learn.deeplearning.ai/chatgpt-prompt-eng

https://github.com/Azure-Samples/openai-dotnet-samples

https://learn.microsoft.com/en-us/dotnet/api/overview/azure/ai.openai-readme?view=azure-dotnet-preview

https://learn.microsoft.com/en-us/dotnet/api/azure.ai.openai?view=azure-dotnet-preview

https://www.nuget.org/packages/Azure.AI.OpenAI

https://github.com/dotnet/interactive

https://github.com/dotnet/csharp-notebooks

