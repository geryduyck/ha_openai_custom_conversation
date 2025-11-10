# OpenAI Custom Conversation

A custom Home Assistant integration for OpenAI Conversation with support for custom OpenAI-compatible endpoints.

## Features

This is an enhanced version of the official OpenAI Conversation integration with the following additional features:

- **Custom Base URL Support**: Configure custom OpenAI-compatible API endpoints
- **Compatible with Local LLMs**: Works with LocalAI, Ollama, LM Studio, and other OpenAI-compatible services
- **All Standard Features**: Retains all features from the official OpenAI integration

## Installation

### HACS (Recommended)

1. Open HACS in Home Assistant
2. Click on "Integrations"
3. Click the three dots in the top right corner
4. Select "Custom repositories"
5. Add this repository URL and select "Integration" as the category
6. Click "Install"
7. Restart Home Assistant

### Manual Installation

1. Copy the `openai_custom_conversation` folder to your `custom_components` directory
2. Restart Home Assistant

## Configuration

1. Go to Settings → Devices & Services
2. Click "Add Integration"
3. Search for "OpenAI Custom"
4. Enter your OpenAI API key
5. Configure your conversation agent or AI task

### Custom Endpoint Configuration

To use a custom OpenAI-compatible endpoint:

1. When configuring the integration, enable "Advanced Settings"
2. In the "Base URL" field, enter your custom endpoint URL
   - For example: `http://localhost:1234/v1` for LM Studio
   - Or: `http://localhost:11434/v1` for Ollama with OpenAI compatibility
3. Leave the field empty to use the default OpenAI API endpoint

## Compatibility

This integration can run alongside the official OpenAI Conversation integration without conflicts.

## Credits

Based on the official Home Assistant OpenAI Conversation integration.

## License

Same license as Home Assistant Core.
