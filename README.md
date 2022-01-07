# Elm Electron guide
Get up and running with a cross-platform desktop app built in Elm.

Electron allows you to render web pages in Elm as native desktop interfaces. Electron runs a web page and manages native desktop interfaces (quit application, set global shortcut, create multiple windows, etc.) using NodeJS. See [jlord.us/essential-electron/](http://jlord.us/essential-electron/) for an excellent, readable conceptual overview of Electron.

This app builds an Elm app that will read data and show a chart with that data.

### Main Stack
* `Electron`
* `Elm` (for the browser window part of Electron)

## Setup
To run, just
```bash
git clone https://github.com/tikal86/starting-with-elm.git
npm install
npm run electron
```
If you change the Elm code do
```bash
npm reactor
```
To see if it is working,

If it is working do
```bash
npm run electron
```
To see it in electron
