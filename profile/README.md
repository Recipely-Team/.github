<div align="center">

<img src="https://raw.githubusercontent.com/Recipely-Team/recipely/main/assets/images/icon.png" width="96" alt="Recipely" />

# Recipely Team

**We build Recipely — talk, import, cook — and the open-source pieces behind it.**

[Website](https://recipely.net) · [About](https://recipely.net/about) · [App Store](https://apps.apple.com/us/app/recipely/id6787391255) · [Google Play](https://play.google.com/store/apps/details?id=com.recipely.app)

</div>

## 📱 Apps

| Project | What it is | Stack |
|---|---|---|
| [**recipely**](https://github.com/Recipely-Team/recipely) | The Recipely app for iOS, Android and the web, from one codebase | React Native · Expo · TypeScript |

## 📦 Libraries

| Project | What it is | Install |
|---|---|---|
| [**live-assistant**](https://github.com/Recipely-Team/live-assistant) | A real-time voice assistant for React Native and the web, on Gemini Live: headless hooks, a drop-in widget and a token server | `npm i @live-assistant/core` |

## 🧪 Tooling

| Project | What it is |
|---|---|
| [**recipely-tests**](https://github.com/Recipely-Team/recipely-tests) | End-to-end tests (Playwright and Maestro) that run against the live app |

The backend API runs from a private repository.

## How we build

- **Clean Architecture and DDD.** Layers depend one way, business rules have no framework in them, and the outside world sits behind interfaces.
- **Machines check the rules.** Strict TypeScript, type-aware lint, structure checks and coverage minimums run on every commit.
- **Every bug fix ships the test that would have caught it**, and a written record of the class of mistake.
- **Security is layered.** TLS with pinned roots, a sealed request envelope, single-use refresh tokens and app attestation.

## Contributing and security

Each repository has its own `README` and contribution notes. Please report vulnerabilities privately to **recep@recipely.net**, never in a public issue.

<sub>The Recipely name, logo and store listings are trademarks; the code in each repository is under the licence stated there.</sub>
