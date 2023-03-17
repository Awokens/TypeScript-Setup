# TypeScript VSC Setup

This repository is simply a TypeScript dev environment for Visual Studio Code, enjoy.

## Installation

[Node.js](https://nodejs.org/en) is required and it is highly recommended to use the latest version.

Clone the repository and have an open terminal set to the current directory of the repo.

Enter the following lines below via terminal
```
npm install --save-dev typescript
```

Now on your right side of your visual studio code editor, click the Run and Debug icon. Then click the run icon (green play symbol) to initialize the preset code to confirm your project is functional. Which should print out to your debug console tab, ``Hello World!``

| File/Directory     | Explanation                                                   |
| ------------------ | ------------------------------------------------------------- |
| .vscode            | A hidden directory that stores VS Code editor configuration   |
| dist               | The directory where compiled code is stored                   |
| node_modules       | The directory where project dependencies are installed        |
| src                | The directory where source code is stored                      |
| README.md          | A markdown file containing information about the project       |
| package-lock.json  | A file used by npm to lock the version of installed packages   |
| package.json       | A JSON file containing metadata about the project and dependencies |
| tsconfig.json      | A JSON file used to configure TypeScript compiler options     |
