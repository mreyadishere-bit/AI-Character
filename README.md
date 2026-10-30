# Hana — Gemini AI Character

One-character Gemini Live voice companion with Three.js/Three-VRM avatar support.

## Start

```bash
npm install
npm run build
npm run dev
```

Open localhost, use Settings to enter your own Gemini API key, grant microphone access, and tap the microphone. Do not commit API keys.

## Limitations

The default companion is an original procedural 3D character, not a professional rigged anime VRM. Import a licensed `.vrm` to use Three-VRM with a proper avatar. Real Gemini calls require a valid key, service access, and browser microphone permissions. This is a web app, not an Android APK. API key input in the browser is for local testing; production should use server-issued ephemeral credentials.

See GitHub Actions for automated build verification.
