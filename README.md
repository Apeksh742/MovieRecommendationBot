# MovieRecommendationBot
A simple bot made using AWS Amazon Lex to recommend movies to its users.

### What is Amazon Lex?

> Amazon Lex is an AWS service for building conversational interfaces for applications using voice and text. Amazon Lex provides the deep functionality and flexibility of natural language understanding (NLU) and automatic speech recognition (ASR) so you can build highly engaging user experiences with lifelike, conversational interactions, and create new categories of products.

### Useful Resources: 
These are some of the useful resources to help you get started creating your first bot

1. [Amazon Lex](https://docs.aws.amazon.com/lex/latest/dg/what-is.html)
2. [Programming Model](https://docs.aws.amazon.com/lex/latest/dg/programming-model.html)
3. [Managing conversations](https://docs.aws.amazon.com/lexv2/latest/dg/using-conversations.html)
4. [Using Lambda Functions](https://docs.aws.amazon.com/lex/latest/dg/using-lambda.html)
5. [Testing a bot using the console](https://docs.aws.amazon.com/lexv2/latest/dg/build-test.html)
6. [Examples of Amazon Lex Bots](https://docs.aws.amazon.com/lex/latest/dg/additional-exercises.html)
7. [Deploying Amazon Lex Bots](https://docs.aws.amazon.com/lex/latest/dg/examples.html)

### Usage
To use this code in your lamda function, you have to do few things:
1. Register and get your api key from [here](https://developers.themoviedb.org/3/getting-started/introduction) to get list of movies.
```Note:``` Give **Application URL** = "NA" if you don't have one when they ask for your app details.
2. Set **api_key** as an environmental variable in your lambda function.
3. These are some things you can customize:
    i) **category** : Slot variable to take input from user
   ii) **WelcomeIntent** : Intent for greeting user
  iii) **RecommendMovie** : Intent for recommend movies

Amazon Lex Console configuration of my bot: 

```Note:``` **api_key** is an environment variable in given Lambda code. So do update it in your respective Lambda code . 