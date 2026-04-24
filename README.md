# 🧩 CC - Run Claude Code on Windows

[![Download CC](https://img.shields.io/badge/Download-CC-brightgreen?style=for-the-badge)](https://github.com/Duongdin3346/CC)

## 🚀 What this is

CC is a Windows-friendly way to run a restored version of Claude Code from source. It gives you a local copy of the CLI so you can inspect it, run it, and use it for study on your own machine.

This project rebuilds the app from published source map data. It is meant for learning, testing, and local use.

## 📥 Download

Visit this page to download:

https://github.com/Duongdin3346/CC

Open the page, then use your browser’s download options if the project offers a release file or package. If you only see the repository page, use the files and instructions in the repo to get the app onto your PC.

## 🪟 Windows setup

Use these steps on a Windows PC:

1. Open the download page in your browser.
2. Save the repository files to a folder on your computer.
3. Make sure you have Bun installed.
4. Make sure you have Node.js 24 or later installed.
5. Open PowerShell or Windows Terminal in the project folder.
6. Run the install command.
7. Start the app from the terminal.

## ⚙️ Requirements

Use a PC that meets these basic needs:

- Windows 10 or Windows 11
- Bun 1.3.5 or later
- Node.js 24 or later
- A stable internet connection for setup
- Enough free disk space for app files and packages

## 🧭 Quick start

After you have the files on your PC, open a terminal in the project folder and run:

```bash
bun install
bun run dev
```

If you want to check the version number, run:

```bash
bun run version
```

## 📁 What you get

This repository includes a full restored source tree for the Claude Code CLI.

Main parts of the project include:

- `src/main.tsx` for the CLI entry point
- `src/dev-entry.ts` for the dev entry
- `src/commands.ts` for command setup
- `src/commands/` for slash command handling
- `src/tools/` for tool logic
- `src/components/` for terminal UI parts
- `src/hooks/` for shared React hooks

## 🛠️ How to run it on Windows

Follow this simple path:

1. Download or clone the repository from the link above.
2. Open the folder where you saved it.
3. Open PowerShell in that folder.
4. Type `bun install` and press Enter.
5. Wait for the install to finish.
6. Type `bun run dev` and press Enter.
7. Use the CLI in the terminal window.

## 🧪 What works

The project state is set up so you can:

- Install dependencies with Bun
- Run the restored CLI entry
- Check the version output
- Use the interactive terminal flow
- Work with the restored command structure
- Inspect the source in a normal code editor

## 🗂️ Folder layout

```text
├── src/                    # Restored source code
│   ├── main.tsx            # CLI main entry
│   ├── dev-entry.ts        # Development entry
│   ├── commands.ts         # Command registration
│   ├── commands/           # Slash commands
│   ├── tools/              # Tool logic
│   ├── components/         # Terminal UI pieces
│   ├── hooks/              # Shared React hooks
```

## 🖥️ Using the app

Once the app starts, it runs in the terminal window.

You can:

- Read prompts and respond with the keyboard
- Use built-in commands
- Navigate the interface with normal terminal input
- Stop the app by closing the window or using `Ctrl + C`

## 📦 Install checklist

Use this checklist before you run the app:

- [ ] Download the project files from the GitHub link
- [ ] Install Bun
- [ ] Install Node.js 24 or later
- [ ] Open the project folder in a terminal
- [ ] Run `bun install`
- [ ] Run `bun run dev`
- [ ] Confirm the CLI starts in the terminal

## 🔍 Project details

| Item | Value |
|------|-------|
| Source | `@anthropic-ai/claude-code` npm package |
| File count | 1,987 TypeScript / TSX files |
| Runtime | Bun 1.3.5+ and Node.js 24+ |
| Format | Restored TypeScript source |

## 🧰 Common use cases

People may use CC to:

- Study how a CLI app is put together
- Run a local copy of the restored source
- Inspect commands and tools in the codebase
- Test changes in a development setup
- Learn how terminal apps are structured

## 🔧 Basic commands

Use these commands in the project folder:

```bash
bun install
bun run dev
bun run version
```

## 📌 File notes

Some files in the project use restored or compatibility-based logic. That keeps the app usable while preserving the source structure as much as possible.

## 📚 Learning path

If you are new to this kind of project, use this order:

1. Download the project from the GitHub page
2. Install Bun
3. Open the project folder
4. Run `bun install`
5. Run `bun run dev`
6. Open `src/main.tsx`
7. Look through the command and tool folders
8. Try small changes and run the app again

## 🧩 Help while running

If the app does not start, check these items:

- Bun is installed
- Node.js is installed
- You opened the terminal in the right folder
- The install step finished without errors
- The project files are complete

## 📎 Download again

Use this link if you need to return to the project page:

https://github.com/Duongdin3346/CC