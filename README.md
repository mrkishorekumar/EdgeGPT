# EdgeGPT

> Private, on-device AI for your phone.

EdgeGPT is an Expo React Native app being built to let people download and run large language models directly on their device. The goal is a useful AI assistant that continues to work without an internet connection and keeps conversations and inference local.

## Vision

- **Offline by default** — use downloaded models without a network connection.
- **Private by design** — keep prompts and inference on the device.
- **Bring your own model** — download and manage supported local LLMs.
- **Fast on-device inference** — planned integration with [ExecuTorch](https://pytorch.org/executorch/).

## Status

Early development. The current repository contains the Expo application foundation; local model downloading and ExecuTorch-powered inference are planned next.

## Tech stack

- [Expo](https://expo.dev/) and React Native
- TypeScript
- Expo Router
- ExecuTorch *(planned)*

## Getting started

### Prerequisites

- Node.js (LTS recommended)
- npm
- Expo Go or an Android/iOS simulator for development

### Install and run

```bash
git clone https://github.com/mrkishorekumar/edgegpt.git
cd edgegpt
npm install
npx expo start
```

From the Expo terminal, choose an Android emulator, iOS simulator, web browser, or scan the QR code with Expo Go.

## Scripts

```bash
npm run start    # Start the Expo development server
npm run android  # Open on Android
npm run ios      # Open on iOS
npm run web      # Open in a browser
npm run lint     # Run Expo linting
```

## Roadmap

- [ ] Design the local model library and download flow
- [ ] Add model storage, management, and deletion controls
- [ ] Integrate ExecuTorch for on-device LLM inference
- [ ] Build an offline chat interface
- [ ] Add model and device performance information

## License

This project is licensed under the [MIT License](LICENSE).
