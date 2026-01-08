# HolyC for VS Code

HolyC language support for Visual Studio Code, including:

- **Syntax highlighting** for HolyC (`.HC`)
- A **file icon theme** forked from VS Code’s built-in **Seti** icon set — including a **HolyC icon**

---

## Features

### HolyC syntax highlighting
- TextMate-based highlighting for HolyC source files.
- Automatic language association for `*.HC` files (or select **HolyC** manually from the language mode picker).

### HolyC file icon theme (Seti fork)
- A lightweight icon theme based on the familiar Seti look.
- Adds icons so HolyC files get their own dedicated icon.

---

## Installation

### From GitHub releases

* Install the most current .vsix from the GitHub releases page

* In VS-Code, right click on the .vsix file and click ```Install Extension VSIX```

### From source (local development)
```bash
git clone https://github.com/LueWasHere/holyc-vscode
cd holyc-vscode
npm install
```

Then press ```F5``` in VS Code to launch an Extension Development Host window.

---

## Usage
### Syntax highlighting
* Open any *.HC file — it should automatically highlight as HolyC.

* If it doesn’t:

  1. Click the language mode in the bottom-right of VS Code (it might say something like Plain Text)

  2. Select HolyC

---

## Enable the HolyC icon theme
1. Open the Command Palette:

   * Windows/Linux: Ctrl+Shift+P

   * macOS: Cmd+Shift+P

2. Type File Icon Theme

3. Choose the HolyC icon theme from the list

![Theme-Change-Guide](https://github.com/LueWasHere/holyc-vscode/blob/main/icons/change-icon-theme.gif?raw=true)

| After enabling the icon theme, HolyC files (like *.HC) should display the HolyC-specific icon in the Explorer.

---

## What files are supported?
* *.HC/hc — HolyC source files
* *.H/h — HolyC source files (variation)
* *.HH/hh — HolyC header/interface files
* *.DD/dd — HolyC data definition files

(If you use additional HolyC-related extensions and want them icon’d/highlighted too, feel free to open an issue or PR.)

---

## License

MIT

---

## Credits

* HolyC language by Terry A. Davis.

* Icon theme is a fork/derivative of VS Code’s Seti icon style, adapted to include HolyC.

* HolyC VS-Code extension created by LueWasHere
