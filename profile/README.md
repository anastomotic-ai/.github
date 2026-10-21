# Anastomotic

**An open source AI agent for your desktop.** Anastomotic works with your files, documents and browser on your own machine, using the AI model you choose. Every action needs your approval.

[Repository](https://github.com/anastomotic-ai/anastomotic) · [Report an issue](https://github.com/anastomotic-ai/anastomotic/issues) · [Contributing guide](https://github.com/anastomotic-ai/anastomotic/blob/main/CONTRIBUTING.md)

## What it does

- **Files:** sort, rename and organize folders by content, type or date
- **Documents:** draft, summarize and rewrite reports, notes and docs
- **Browser:** research a topic or fill out web forms for you
- **Skills:** save repeatable workflows and run them again, or on a schedule

## Why Anastomotic

- **Local first:** the app, your task history and your settings stay on your machine. You choose which folders it can access.
- **Your choice of model:** use your own API key, or run a local model with Ollama or LM Studio and keep everything offline.
- **You stay in control:** you approve each action, can see what the agent is doing, and can stop it at any time.
- **Open source:** MIT licensed. Read it, fork it, improve it.

When you use a cloud model, your prompts and the file content needed for the task are sent to that provider.

## Supported providers

| Type            | Providers                                                                                                                                                      |
| :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Model APIs      | Anthropic, OpenAI, Google Gemini, xAI, DeepSeek, Moonshot AI, Z-AI, MiniMax, Groq, Together AI, Fireworks AI, Nebius AI, Venice AI, NVIDIA NIM, GitHub Copilot |
| Cloud platforms | AWS Bedrock, Google Vertex AI, Azure AI Foundry                                                                                                                |
| Local models    | Ollama, LM Studio, HuggingFace Local                                                                                                                           |
| Gateways        | OpenRouter, LiteLLM, any OpenAI-compatible endpoint                                                                                                            |

## Get started

Installers for Windows, macOS and Linux are on the way. Until then, run it from source:

```bash
git clone https://github.com/anastomotic-ai/anastomotic.git
cd anastomotic
pnpm install
pnpm dev
```

Requires Node.js 22 and pnpm 9. See the [contributing guide](https://github.com/anastomotic-ai/anastomotic/blob/main/CONTRIBUTING.md) for platform notes.

## Contributing

Bug reports, fixes and new skills are welcome. Start with the [contributing guide](https://github.com/anastomotic-ai/anastomotic/blob/main/CONTRIBUTING.md), then open an issue or pull request.

## License

[MIT](https://github.com/anastomotic-ai/anastomotic/blob/main/LICENSE)
