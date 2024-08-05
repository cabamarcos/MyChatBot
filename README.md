# MyChatBot

This repository contains a simple implementation of an AI chatbot using [Web-LLM](https://github.com/mlc-ai/web-llm) and web workers to increase load performance.

To use this you an open this link:

https://cabamarcos.github.io/MyChatBot/

The model I used is Gemma, which is not good but its small. If you want to change the model follow this steps:

1. Clone the repository.

```bash
git clone https://github.com/cabamarcos/MyChatBot.git
```

2. Open the file script.js.

3. Change the selected model with any model available in this [link](https://github.com/mlc-ai/web-llm/blob/main/src/config.ts).

The best model available is llama3. Change it doing this:

```JavaScript
const SELECTED_MODEL = 'Llama-3-8B-Instruct-q4f32_1-MLC-1k'
```

# TODO

- Deploy it somewhere and create a database that stores the chats, making it possible to access your last conversations.
