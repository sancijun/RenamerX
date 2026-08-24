# Troubleshooting RenamerX

## Installation or resource download does not finish

1. Confirm that the operating system and hardware meet the [current requirements](https://renamerx.com/docs/getting-started/installation).
2. Keep RenamerX open and maintain a stable internet connection until verification completes.
3. Confirm that enough free storage is available for the selected provider's resources.
4. Retry from System Status. If the problem continues, record the visible error message without including private file data.

## An AI provider cannot be activated

1. Confirm the endpoint, model ID, and credentials.
2. Verify that the model supports the visual and structured-output capabilities required by RenamerX.
3. For Ollama or LM Studio, confirm that the local service is running and reachable from the same device.
4. For cloud providers, check account quota, rate limits, billing, and regional availability.
5. Run the connection test again after changing any provider setting.

## A suggested filename is not useful

1. Confirm that the selected naming template requests fields that the file can actually provide.
2. Check the [supported file types](https://renamerx.com/docs/getting-started/supported-file-types) and whether the file contains readable text, metadata, or a usable visual preview.
3. Edit or retry the suggestion before Apply.
4. Use controlled terms when fields such as subject, type, status, organization, or project need consistent vocabulary.
5. Test new rules on a small batch before enabling a Watch Folder.

## An applied change needs to be restored

Use Undo from the corresponding RenamerX workflow while the operation record is available. Avoid manually moving the affected files before Undo, because the expected paths may no longer match.

## Still need help?

Read the full [official troubleshooting guide](https://renamerx.com/docs/help-support/troubleshooting), then choose the appropriate channel in [SUPPORT.md](../SUPPORT.md). Remove confidential information before posting publicly.
