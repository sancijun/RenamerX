# RenamerX release notes

This file summarizes public RenamerX releases. Installation channels may publish updates at slightly different times while store review and rollout complete.

## v1.2.2

RenamerX v1.2.2 adds more control over where AI processing happens, simplifies first-time setup, and improves delivery on macOS and Windows.

### What's new

- Choose RenamerX Built-in, Ollama, LM Studio, OpenAI, Google Gemini, or a custom OpenAI-compatible service as the AI provider.
- Configure and test the selected provider during first-time setup or later in Preferences.
- Use only the core extraction components with an external provider, avoiding the built-in model download when on-device inference is not needed.
- Store API keys encrypted on the device and keep them out of regular preferences, logs, and diagnostic exports.
- See the active provider and required-component readiness in System Status.

### Fixes and improvements

- Improved connection, authentication, model, rate-limit, and quota error messages.
- Improved compatibility with Ollama and Google Gemini.
- macOS builds are signed and notarized by Apple; signed updates continue to install through RenamerX.
- Windows installation and updates are delivered through Microsoft Store.

### Platform support

RenamerX v1.2.2 officially supports macOS and Windows. Linux is not an officially supported or publicly distributed platform.

## Update channels

- macOS: install with `brew install --cask renamerx` or download from [renamerx.com](https://renamerx.com/).
- Windows: install and update through [Microsoft Store](https://apps.microsoft.com/detail/9N03KWP1XM0D).
