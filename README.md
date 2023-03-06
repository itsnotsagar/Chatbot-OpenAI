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

# Screenshots
<p align="center">
<img width="1552" alt="Screenshot 2023-03-06 at 5 32 16 PM" src="https://user-images.githubusercontent.com/56265949/223105597-eebda6c1-de37-486c-a4e2-aeee25246c0d.png">
<img width="1552" alt="Screenshot 2023-03-06 at 5 32 45 PM" src="https://user-images.githubusercontent.com/56265949/223105633-de96c647-ffbe-4fb2-ac7e-df34d642bfec.png">
<img width="1552" alt="Screenshot 2023-03-06 at 5 33 06 PM" src="https://user-images.githubusercontent.com/56265949/223105659-3ad0049b-3107-4af5-9440-4e236840d406.png">
<img width="1552" alt="Screenshot 2023-03-06 at 5 33 42 PM" src="https://user-images.githubusercontent.com/56265949/223105747-d5b216af-359f-4faf-ae06-f0c45c3985c6.png">
</p>
