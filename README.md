# Copilot Instructions

A simple guide to customizing Copilot's behavior via instruction files.

## Overview

This project provides a way to enhance and tailor GitHub Copilot's code generation by adding custom instruction files to your projects or globally in your VS Code environment.

- [4d instructions](4d.instructions.md)

## Installation

### For a Specific Project

1. Create a `.github/instructions` directory in your project (if it doesn't exist).
2. Copy all `*.instructions.md` files you want Copilot to use into this directory.
3. Ensure the VS Code setting ⚙ `chat.codeGeneration.useInstructionFiles` is enabled.

### For All VS Code Projects (Global Setup)

1. Download this project.
2. Add the path to the downloaded project in your VS Code settings under ⚙ `chat.instructionsFilesLocations`.

## Usage

- Copilot will automatically read and apply the instruction files from your specified locations.

## Requirements

- VS Code with Copilot extension installed
- The required settings enabled as described above

## License

[MIT](LICENSE)

---

Enhance your coding experience by guiding Copilot with your own instructions!
