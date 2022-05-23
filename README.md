# vscode-default-setup

- [Table of contents](#)
  - [Required Extensions](#required-extensions)
  - [Font Families](#font-families)
  - [VSCode Defalut Settings](#vscode-default-settings)
  - [Five Server Settings](#five-server-settings)
  - [Bottom Line](#bottom-line)

## Required Extensions
- Themes:
  - Learn with Sumit Theme - Sumit Saha
  - Monokai Pro - monokai
- Extentions:
  - Live Server (Five Server) - Yannick
  - Material Icon Theme - Philipp Kief
  - Path Intellisense - Christlan Kohler

## Font Families
- Operator Mono (Only for personal use) - Premium Font
- FiraCode - Free
- JetBrains Mono - Free
- FiraMono Nerd Font - Free
- FiraCode NF - Free

## VSCode Default Settings
All the required settings are listed here. VSCode Default [settings.json]('./settings.json') file.

## Five Server Settings
Create a file named fiveserver.config.js in the project root & copy the following code or take from the repo:
```sh
// fiveserver.config.js
module.exports = {
  highlight: true, // enable highlight feature
  injectBody: true, // enable instant update
  remoteLogs: true, // enable remoteLogs
  remoteLogs: "yellow", // enable remoteLogs and use the color yellow
  injectCss: false, // disable injecting css
  navigate: true, // enable auto-navigation
};
```

## Bottom Line
That's not all!