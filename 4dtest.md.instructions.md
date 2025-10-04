---
applyTo: '**/*.4dm'
---

# 4D Test Instructions
This file contains instructions for running tests on 4D files.

## Prerequisites
- Ensure you have 4D installed on your system. Possile paths include:
  - `tool4d.app/Contents/MacOS/tool4d` if exists in project
  - `tool4d` (if in $PATH)
  - or `$TOOL4DBIN` environment variable
  - or use most recent one in `$HOME/Library/Application Support/Code/User/globalStorage/4D.4d-analyzer/tool4d/<version>/<changelist>/tool4d.app/Contents/MacOS/tool4d` (use find command to locate it)
  
## Running Tests

> <tool4dbin> --project <projectfile> --dataless --skip-onstartup --startup-method <thetestmethod>
where:
- `<tool4dbin>` is the path to your 4D binary (e.g., 4D, tool4d, etc.)
- `<projectfile>` is the path to your .4DProject file in Project folder
- `<thetestmethod>` is the method that contains your tests
