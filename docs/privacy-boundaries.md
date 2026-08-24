# RenamerX privacy boundaries

RenamerX is local-first, but “local-first” does not mean every optional configuration is local or that the application never uses the network.

## File processing and AI providers

| Provider | Where naming inference happens | Practical boundary |
| --- | --- | --- |
| RenamerX Built-in | On the device | Supported file content used for inference stays on the device after required resources are installed. |
| Ollama | Configured endpoint | Usually local, but the endpoint may be remote depending on the user's configuration. |
| LM Studio | Configured endpoint | Usually local, but the endpoint may be remote depending on the user's configuration. |
| OpenAI | Provider cloud | Required content, previews, metadata, and naming settings are sent to OpenAI under its terms. |
| Google Gemini | Provider cloud | Required content, previews, metadata, and naming settings are sent to Google under its terms. |
| Custom | Configured endpoint | The endpoint owner, location, retention, billing, and security controls depend on the user's configuration. |

RenamerX does not silently switch to another provider when a configured provider fails. Review the active provider before processing sensitive material.

## Other network activity

Network services may be used for:

- application and resource downloads;
- software updates;
- purchases, license issuance, activation, and validation;
- website analytics;
- diagnostics and error reporting;
- user-requested support.

The current [Privacy Policy](https://renamerx.com/privacy) and [Security and Privacy guide](https://renamerx.com/docs/help-support/security-and-privacy) are authoritative for public data-handling disclosures.

## Public issue safety

Before opening an issue, remove:

- personal or client filenames and full file paths;
- document text, previews, screenshots, and metadata;
- API keys, license keys, access tokens, and endpoint credentials;
- names, email addresses, account identifiers, and purchase records;
- unredacted diagnostic archives.

Use synthetic test files whenever possible. Send private support and security reports through the channels in [SUPPORT.md](../SUPPORT.md) and [SECURITY.md](../SECURITY.md).
