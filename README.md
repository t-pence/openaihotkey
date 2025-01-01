# openaihotkey# OpenAIHotkey

This AutoHotkey script sends text in your clipboard to the OpenAI API. 
It also supports contextual conversations by saving message history.

## Requirements
- [AutoHotkey](https://www.autohotkey.com/) (v1 or v2, depending on your code version)

## Usage
- Copy any text you want to send to the API.
- Press `Ctrl+Alt+G` for a single query.
- Press `Ctrl+Alt+H` for a contextual conversation.

## Setup
- In `src/OpenAIHotkey.ahk`, you’ll see `apiKey := "sk-xxxxxx"`. **Do not use your real API key here.**
- Either remove your key or store it in a separate file that you ignore with `.gitignore`.

## Contributing
Pull requests or ideas are welcome!
