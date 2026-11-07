# Zenod for Gemini CLI

<img src="icon.png" width="96" alt="Zenod">

**Zenod — memory you own, fed from WhatsApp.**

Send notes and voice memos on WhatsApp; Zenod files them into a Markdown vault you own on GitHub or Google Drive and answers from it with sources.

## Install

```sh
gemini extensions install https://github.com/zenod-ai/zenod-gemini
```

The first time Gemini CLI uses a Zenod tool it opens a browser so you can sign in to Zenod (OAuth). You need a Zenod account (sign in with Google at [cloud.zenod.dev](https://cloud.zenod.dev)) and a GitHub repository or Google Drive folder for the vault.

## What it does

Zenod is a personal memory agent. Tell it things the way you already talk: a WhatsApp message, a voice note, a pasted email, a meeting transcript. Zenod keeps the original as evidence, files the meaning onto the right page of your vault, and links every page back to its source.

Your memory lives in ordinary Markdown in storage you own, a GitHub repository or a Google Drive folder, so you can read it, edit it, open it in Obsidian or take it elsewhere at any time. Every write comes back with a receipt: the page it touched and the commit or file it saved.

With this connector, Claude can search your memory, read a note, store something new and ask a question that spans many notes. Answers cite the vault pages they came from, so you can check them.

Zenod Hosted costs €9/month + VAT and includes managed AI usage and WhatsApp. Zenod is open source (AGPL-3.0) and can be self-hosted free with your own AI key.

## Example prompts

1. "Remember that my car insurance with Mapfre renews on 14 March."
2. "When does my passport expire?"
3. "What did I send myself on WhatsApp last week about the garden?"
4. "Open my note on the Barcelona flat viewing."
5. "File this meeting transcript into my vault."

## Links

- Connect guide: https://zenod.dev/connect
- Source: https://github.com/zenod-ai/zenod
- Privacy: https://zenod.dev/legal/privacy.html · Terms: https://zenod.dev/legal/terms.html
- Support: support@zenod.dev

Keywords: memory, personal memory, second brain, notes, knowledge base, PKM, WhatsApp, voice notes, Markdown, Obsidian, GitHub, Google Drive, journal, recall, citations, long-term memory.
