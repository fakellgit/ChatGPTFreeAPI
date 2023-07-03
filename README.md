# ChatGPTFreeAPI

Welcome to the ChatGPT API Free, API that allows you to access OpenAI's ChatGPT API for free.

ChatGPT API Free is a powerful tool that allows users to generate responses to prompts using the GPT-3.5 language model. The API is easy to use and can be accessed by sending a POST request to a specific endpoint. 


## Usage

To use ChatGPT API Free, simply send a POST request to the following endpoint:

```
http://fakell.raidghost.com/v1/chat/completions/
```

For instance, to generate a response to the prompt "Hello, how are you?" using the `gpt-3.5-turbo` model, send the following `curl` command:

```sh
curl http://fakell.raidghost.com/v1/chat/completions/ \
  -H 'Content-Type: application/json' \
  -d '{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Hello, how are you?"}],
  "stream": false
}'
```

If you need more information on how to use the ChatGPT API Free, you can consult the official [API documentation provided by OpenAI](https://platform.openai.com/docs/api-reference/chat/create). The documentation is very comprehensive and provides detailed information on how to use the API, along with sample code snippets to help you get started.

## Follow me!

If you find the ChatGPT API Free useful, you can stay up-to-date on the latest developments by following me. By following [me](https://github.com/fakellgit), you will be the first to know about new features, updates, and improvements to the API.

## Author
Fahendrena
[fakellyh@gmail.com](mailto:fakellyh@gmail.com).


