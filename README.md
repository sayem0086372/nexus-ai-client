# Nexus AI Client

A modern Android AI client designed to connect with multiple AI providers using user-supplied API keys.

## Highlights

- Modern Android / Jetpack Compose UI
- Provider-based architecture for AI integrations
- Secure local API-key handling via Android Keystore
- Streaming response support
- Extensible provider adapters
- Clean separation between UI, models, providers, and security

## Project structure

```text
app/src/main/java/com/example/
├── model/       # AI models and chat data
├── provider/    # Provider adapters and HTTP client
├── security/    # Secure key storage
└── ui/          # Compose UI and theme
```

## Getting started

1. Open the project in Android Studio.
2. Let Gradle sync the project.
3. Configure your provider API keys locally. Never commit real API keys.
4. Run the `app` configuration on an Android device or emulator.

## Security

API keys are intended to be supplied by the user and stored locally. Keep `.env` and other secret-bearing files out of Git.

## Status

🚧 Active development.

## License

MIT License. See `LICENSE`.
