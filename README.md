# AisSembly IDE

This repository includes an example configuration for connecting to an [Ollama](https://ollama.ai) instance using `llm_functions.json`.

## Connecting to Ollama

Create an `llm_functions.json` file with the provider set to `ollama`, pointing to the Ollama server and specifying the model to use. For example:

```json
{
  "llm": {
    "provider": "ollama",
    "endpoint": "http://localhost:11434",
    "model": "llama2"
  }
}
```

A fuller example including a function definition is available at [`examples/ollama/llm_functions.json`](examples/ollama/llm_functions.json).
