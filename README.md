# Introduction
A simple chatbot made with the OpenAI Completions API using the same AI
language model (text-davinci-003) as ChatGPT!
<br><br>
The flagship AI chatbot from OpenAI, ChatGPT, has quickly become a global sensation due to its advanced suite of AI language models. In just two months after its release, ChatGPT gained over 100 million monthly active users, setting a new record as the fastest growing consumer application ever. Many developers have leveraged the same APIs as ChatGPT to create innovative applications such as chatbots and content writing tools. In this project, we will explore how to use the OpenAI Completions API by creating a simple chatbot.

# The API
The OpenAI Completions API is relatively straightforward. We must specify the `model` to use, and provide a `prompt` -- that's basically it, though there are other parameters we can use to fine-tune things. The API will then return a "completion".
<br><br>
For the `model`, we'll be making use of the Davinci GPT-3 language model (`text-davinci-003`), which according to OpenAI, is their "most capable" model and it's among the same family of GPT-3 natural language models used by ChatGPT itself.

# Prerequisite
Install the below softwares in your machine before running the commands given in `Steps`.
1. `VS Code` 
2. `node`
3. `reactJS`
4. `yarn`

# Steps
1. Clone the repo.
```
git clone https://github.com/itsnotsagar/Chatbot-OpenAI
```
2. Open the repo in `VS-Code`.
3. Create a `.env` file and make sure to paste any contents of `.env.example` into it and paste your API key in `OPENAI_API_KEY =' '`.
4. Install the required dependencies and modules.
```
npm install
```
5. Start the development server.
```
npm run dev
```
6. Open project in browser.<br>
From a web browser, open `localhost:3000`.
