# ChatGPTFreeAPI

Welcome to the ChatGPT API Free, an API that grants access to OpenAI's ChatGPT API at no cost. This API empowers students and individuals to generate responses based on prompts, utilizing the powerful GPT-3.5 language model. It's easily accessible through a simple process by sending a POST request to a specific endpoint.

## Usage

To utilize ChatGPT API Free, send a POST request to the provided endpoint:

```
https://api-fakell.x10.mx/v1/chat/completions/
```

For example, to generate a response to the prompt "Hello, how are you?" using the `gpt-3.5-turbo` model, use the following `curl` command:

```sh
curl https://api-fakell.x10.mx/v1/chat/completions/ \
  -H 'Content-Type: application/json' \
  -d '{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Hello, how are you?"}],
  "stream": false
}'
```

For further instructions on how to use ChatGPT API Free, refer to the official [API documentation provided by OpenAI](https://platform.openai.com/docs/api-reference/chat/create). This comprehensive documentation offers detailed insights on API usage, complete with code samples to assist in starting your project.

## Limit

The ChatGPTFreeAPI has a limitation of 5 requests per minute, which is well-suited for personal projects.

## Stay Connected!

If you find the ChatGPT API Free valuable, you can keep yourself updated on the latest developments by following me. Following [me](https://github.com/fakellgit) ensures you're the first to know about new features, updates, and enhancements to the API.

## Author
Fahendrena
[fakellyh@gmail.com](mailto:fakellyh@gmail.com)
