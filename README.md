# Tavinor

A free desktop assistant for Windows that lives in the notch at the top of your screen. Touch the top edge and it drops down. No hotkey, no app to launch.

**[Download the latest version](https://github.com/PandaOnDiet/tavinor-releases/releases/latest)**: `Tavinor-Setup-<version>.exe`

This repository holds the installer only. The source code is not public.

## What it does

- **Small things stay on your laptop.** Fixed commands like volume, timers and tasks run instantly and offline. Loosely worded commands go to a small model running on your own machine. Only real questions go out, to the provider you pick (Ollama, Anthropic, OpenAI, Google Gemini, Groq, OpenRouter or NVIDIA). API keys are kept in Windows Credential Manager, never in a file.
- **Answer Claude Code from the notch.** Connect Claude Code in Settings, and its permission prompts become an Allow / Deny / Terminal card in the notch. If you don't click within 60 seconds, Claude Code asks in the terminal as usual.
- **Lock-screen widgets.** Small widgets for weather, air quality, next meeting, tasks and focus. Or describe your own in one sentence ("my meeting in red when it's under 10 min, otherwise the weather"), and Tavinor reads the rules back to you in plain words.
- **It talks back, offline.** Replies can be read aloud by a natural voice that runs locally.
- **Pick its brain.** Download a local model from Settings, from Tiny (0.5 GB) to Very heavy (18.6 GB). It warns you when your laptop doesn't have the memory for one.
- **Focus mode** closes the sites that eat your time. **Notes** are found by meaning. **Tasks, habits and reminders** live in the notch and on the Windows widget board.
- **It asks before it touches your files**, and file clean-ups can be undone.
- It has a face. Spin the cursor in circles and it gets dizzy.

## Install

1. Download `Tavinor-Setup-<version>.exe` from [Releases](https://github.com/PandaOnDiet/tavinor-releases/releases/latest).
2. Run it. The installer is **not code-signed yet**, so Windows SmartScreen will warn you: click **More info**, then **Run anyway**.
3. Move your cursor to the top edge of the screen.

**Requirements:** Windows 10 (version 2004) or Windows 11. Lock-screen and widget-board widgets need Windows 11. The local lanes and local answers use [Ollama](https://ollama.com); Tavinor offers to get it for you.

## Your data

Settings, notes, tasks and chat history are stored on your own machine, in `%APPDATA%\Tavinor`. What leaves your machine is the questions you send to the answer provider you chose, and lookups you switch on, such as the weather for your city.

## Feedback

Found a bug or want a feature? [Open an issue](https://github.com/PandaOnDiet/tavinor-releases/issues).
