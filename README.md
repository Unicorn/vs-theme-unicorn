<p align="center">
  <a href="https://unicornagency.com/">
    <img alt="Unicorn banner" src="https://user-images.githubusercontent.com/209344/73117916-f3311080-3f1a-11ea-9e95-ff3f629e54dc.png">
  </a>
</p>

---

<p align="center">
  <!-- marketplace version -->
  <a href="https://marketplace.visualstudio.com/items?itemName=Unicorn.vs-theme-unicorn">
    <img alt="marketplace version" src="https://img.shields.io/vscode-marketplace/v/Unicorn.vs-theme-unicorn.svg?maxAge=3600&style=for-the-badge&labelColor=1C1E26&color=F7B3A1">
  </a>
  <!-- downloads -->
  <a href="https://marketplace.visualstudio.com/items?itemName=Unicorn.vs-theme-unicorn">
    <img alt="downloads" src="https://img.shields.io/visual-studio-marketplace/d/Unicorn.vs-theme-unicorn.svg?maxAge=3600&style=for-the-badge&labelColor=1C1E26&color=F7B3A1">
  </a>
  <!-- rating -->
  <a href="https://marketplace.visualstudio.com/items?itemName=Unicorn.vs-theme-unicorn">
    <img alt="rating" src="https://img.shields.io/visual-studio-marketplace/stars/Unicorn.vs-theme-unicorn.svg?maxAge=86400&style=for-the-badge&labelColor=1C1E26&color=F7B3A1">
  </a>
</p>

<p align="center">
  <img alt="preview" src="https://user-images.githubusercontent.com/209344/73117958-7488a300-3f1b-11ea-94fb-b9e45ab385a1.png" width="90%">
</p>


## Installation

1. Open the **Extensions** sidebar in VS Code
2. Search for `Unicorn Theme`
3. Click **Install**
4. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`
5. Select **Preferences: Color Theme** and choose a Unicorn Theme variant.
6. Enjoy! 🎉 Also, check out some of the personalization options below...

## Personalization

Tastes change all the time. Fortunately, VS Code makes it easy to customize just about every aspect of your editor.
If you want to change something, open the **Command Palette** and select **Preferences: Open Settings (JSON)**. Here, you can override VS Code's defaults or Unicorn's colors. Check out some of the personalization options below to customize Unicorn Theme to your liking.

_For more info on theming, visit the [Theme Authoring Guide](https://code.visualstudio.com/api/extension-capabilities/theming) and [Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)._

### Contrast

To add a border between sections of the editor, add the following to your settings...

```
"workbench.colorCustomizations": {
  "contrastBorder": "#16161C"
}
```

Or for Bright variants...

```
"workbench.colorCustomizations": {
  "contrastBorder": "#1A1C231A"
}
```

### Italics

The normal theme only uses italics in a few places. If you would prefer no italics at all, you can configure this in your settings...

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "No italics",
      "scope": ["comment", "markup.quote", "variable.language", "variable.parameter"],
      "settings": {
        "fontStyle": "normal"
      }
    }
  ]
}
```

### Tag Brackets `<>`

For gray rather than red brackets around HTML tags...

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "Tag brackets",
      "scope": ["punctuation.definition.tag"],
      "settings": {
        "foreground": "#BBBBBB"
      }
    }
  ]
}
```

## Contributing

Check out the [contributing guide](CONTRIBUTING.md) to learn how you can report issues and help make changes.

Always be sure to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

[MIT](LICENSE) © [Unicorn Agency](https://unicornagency.com)
