# FAIZAN NEXUS AI

A premium local-first developer intelligence and automation dashboard tailored for **FaizanLabs-EXE**.

## Features

- GitHub public profile and repository intelligence
- AI repository metadata auditor
- Multi-agent Wikipedia research with visible sources
- OpenRouter live model catalog and free-priced filter
- Streaming AI output and model routing
- Open-Meteo location search and 7-day forecast
- Local no-code automation workflows
- IndexedDB knowledge vault, logs, settings and cached data
- Command palette, responsive interface, dark/light themes
- Local JSON export

## Deploy on GitHub Pages

1. Upload all seven files to a repository root.
2. Open repository **Settings > Pages**.
3. Choose **Deploy from a branch**.
4. Choose `main` and `/(root)`, then save.
5. Open the published site.
6. In **Settings**, paste a restricted OpenRouter API key.
7. In **Model Router**, select a default model.

## Included APIs

- GitHub REST API for public profile and repository metadata
- MediaWiki Action API for anonymous cross-origin research
- Open-Meteo geocoding and forecast APIs
- OpenRouter Models and Chat Completions APIs

## Security and architecture

This is a static browser application. The OpenRouter key is stored in the user's own IndexedDB and is sent only to OpenRouter. Never commit an API key. Prefer a restricted key with a spending limit.

Static GitHub Pages cannot execute a persistent backend. Interval automations operate only while the page remains open and active. Browser storage may be deleted by the user or browser, so export important vault content regularly.

Direct public API features are rate-limited by their providers. Retrieved data and AI output are rendered as text or escaped HTML.

## Signature

**⟦ 𝐁𝐔𝐈𝐋𝐓 𝐁𝐘 𝐅𝐀𝐈𝐙𝐀𝐍 ⟧**
