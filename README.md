# gpt3-demo

A collection of interactive GPT-3 demos in a NextJS+Mantine web app.

<img src="https://user-images.githubusercontent.com/220799/188976628-aee63401-55fa-40c9-81d7-028758906d20.png"
   width="600" alt="Screenshot of npm app with GPT-3 demos" />

## Bootstrap

Run the webserver locally to interact with the demo

### Open AI token required

Create one here: [https://openai.com/api/](https://openai.com/api/)

```sh
cp .env.local.example .env.local
```

Declare your API token in `.env.local`

### Codex note

Codex is in private beta and requires approval from Open AI. See details here: https://openai.com/blog/openai-codex/

### Starting the server

```sh
npm install
npm run dev
```

## Pre-commit setup
```sh
python3 -m pip install pre-commit
pre-commit --install
```
