<p align="center">
  <img width="180" src="./icon.png" alt="BingGPT">
  <h1 align="center">BingGPT</h1>
  <p align="center">Desktop application of new Bing's AI-powered chat</p>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0">
    <img alt="License" src="https://img.shields.io/badge/license-Apache_2.0-green">
  </a>
  <a href="https://github.com/dice2o/BingGPT/releases">
    <img alt="Downloads" src="https://img.shields.io/github/downloads/dice2o/BingGPT/total?color=blue">
   </a>
</p>

## 说明
很显然，这是个fork。最新版可能没空打包，请自行编译。但你可以瞅一眼Release，能用就不必追求最新。

## 安装
1. `git clone`
2. `yarn install`
3. `yarn run make`

## 此fork已经解决的问题
1. 根治白屏问题。
2. 支持复制粘贴快捷键。
3. 根治落回中国区的问题。（每次启动时会解除cookie毒化。使用中落回请重启app解毒。）

- [BingGPT-0.3.7-win32-x64-Setup.exe](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-win32-x64-Setup.exe) (Installer)
- [BingGPT-0.3.7-win32-x64.zip](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-win32-x64.zip) (Portable)
- [BingGPT-0.3.7-win32-arm64-Setup.exe](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-win32-arm64-Setup.exe) (Installer)
- [BingGPT-0.3.7-win32-arm64.zip](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-win32-arm64.zip) (Portable)

### macOS

- [BingGPT-0.3.7-darwin-arm64.dmg](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-darwin-arm64.dmg) (Apple Silicon)
- [BingGPT-0.3.7-darwin-x64.dmg](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-darwin-x64.dmg) (Intel chips)

### Linux

- [BingGPT-0.3.7-linux-x64.deb](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-linux-x64.deb)
- [BingGPT-0.3.7-linux-arm64.deb](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-linux-arm64.deb)
- [BingGPT-0.3.7-linux-x64.rpm](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-linux-x64.rpm)
- [BingGPT-0.3.7-linux-arm64.rpm](https://github.com/dice2o/BingGPT/releases/download/v0.3.7/BingGPT-0.3.7-linux-arm64.rpm)

## Usage

- Sign in to your Microsoft account
- Start chatting

**Note: VPN is required if new Bing is not available in your area. Make sure `bing.com` and its subdomains are included in proxy rules.**

**If the app cannot be opened in macOS, execute the following command in Terminal app**

```
sudo xattr -d com.apple.quarantine /Applications/BingGPT.app
```

## Features

- Chat with new Bing without installing Microsoft Edge or browser plugins
- Export full conversation to Markdown, PNG or PDF
- Customize appearance (theme & font size)
- Keyboard shortcuts
- Multi-platform

## Shortcuts

| Action            | Shortcut                                        |
| ----------------- | ----------------------------------------------- |
| New topic         | <kbd>Ctrl/Cmd</kbd> + <kbd>N</kbd>              |
| Switch tone       | <kbd>Ctrl/Cmd</kbd> + <kbd><</kbd> <kbd>></kbd> |
| Quick reply       | <kbd>Ctrl/Cmd</kbd> + <kbd>Number</kbd>         |
| Focus on textarea | <kbd>Ctrl/Cmd</kbd> + <kbd>I</kbd>              |
| Stop responding   | <kbd>Ctrl/Cmd</kbd> + <kbd>S</kbd>              |
| Always on top     | <kbd>Ctrl/Cmd</kbd> + <kbd>T</kbd>              |
| Reload            | <kbd>Ctrl/Cmd</kbd> + <kbd>R</kbd>              |
| Set font size     | <kbd>Ctrl/Cmd</kbd> + <kbd>+</kbd> <kbd>-</kbd> |

<kbd>Ctrl</kbd> - Windows and Linux

<kbd>Cmd(⌘)</kbd> - macOS

## Screenshot

<img width="601" src="./screenshot.png" alt="BingGPT Screenshot">

## License

Apache-2.0 License
