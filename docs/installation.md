# Install and update RenamerX

RenamerX officially supports macOS and Windows.

## macOS

Install the signed and notarized universal application with Homebrew:

```bash
brew install --cask renamerx
```

Upgrade through Homebrew:

```bash
brew upgrade --cask renamerx
```

You can also download the current disk image from [renamerx.com](https://renamerx.com/). RenamerX checks for signed macOS updates inside the application.

## Windows

Install RenamerX from [Microsoft Store](https://apps.microsoft.com/detail/9N03KWP1XM0D). Microsoft Store delivers future Windows updates.

## First launch

RenamerX asks you to choose an AI provider and download the components required by that choice:

- **RenamerX Built-in** includes an on-device model and requires the larger resource download.
- **Ollama, LM Studio, OpenAI, Google Gemini, or Custom** use the configured service and need only the core file-reading components.

Keep RenamerX open until the resource download and verification finish. Current operating-system, hardware, storage, and provider requirements are maintained in the [official installation guide](https://renamerx.com/docs/getting-started/installation).

## Start safely

Use a small, non-critical folder for the first batch. Review all suggested names before Apply. Prove a template in Batch Rename before reusing it with a Watch Folder or Auto Apply.
