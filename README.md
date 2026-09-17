![qUtils](https://cdn.modrinth.com/data/cached_images/96b30d613fa39d4687b703393e5795e928688dba.png)

 <div align="center">
  <a href="https://github.com/QwertyyDev/qUtils">
    <img src="https://cdn.modrinth.com/data/cached_images/b6b08e634ac21529fb61b12fc4ff436290a42d0f.png" alt="Github" width="100">
  </a> 
  <a href="https://modrinth.com/plugin/qutils">
    <img src="https://cdn.modrinth.com/data/cached_images/0f76ddbf67c6103e8265d521ccd6ec9aff6e0dae.png" alt="Modrinth" width="100">
  </a> 
  <a href="https://discord.gg/aQTWMEMwC9">
    <img src="https://cdn.modrinth.com/data/cached_images/b5c430507784e3ae83d35c6ec72e2fd84647ec99.png" alt="Discord" width="100">
  </a>
</div>

A utility plugin that brings text formatting tools to your server staff through a single GUI, accessed with the **/utils** command. No websites, no manual color codes — everything happens in-game.

<center>

![Features](https://cdn.modrinth.com/data/cached_images/7e70a283aa34a3806f7dbe73f957643a857fe398_0.webp)

</center>

**Small Caps Converter**

Converts regular text into small caps unicode characters. Useful for announcements, scoreboard titles, and hologram text.

- Type your text in chat and get an instant conversion
- Click the result to copy it

**Gradient Maker**

Generates two-color gradient text with HEX support, plus toggleable bold, italic, underline, and strikethrough styling.

- Pick your first and second color from an in-game color palette
- Combine the gradient with any text style toggle
- Result is sent to chat, ready to copy

**Emoji and Symbol Copier**

A symbol library covering decorative, weather, music, gaming, geometric, arrow, superscript, and subscript characters.

- Browse by category directly from the GUI
- Click a symbol to send it straight to chat

<center>

![Permissions](https://cdn.modrinth.com/data/cached_images/3286421d59bf3e5f1fe5608ddb2246df34024a91_0.webp)

</center>

| Permission | Description | Default |
|---|---|---|
| `qutils.use` | Allows access to the **/utils** command | op |

<center>

![Configuration](https://cdn.modrinth.com/data/cached_images/430ce407db153d584c42ed7bc5978d62da526f54_0.webp)

</center>

The plugin ships with a `config.yml` for customizing prefixes and in-game messages:

```yaml
messages:
  prefix: '&8[&bGlyph&fUtils&8]&r'
  no-permission: '&cYou do not have permission to use this command.'
  main-menu-title: '&8⏷ &bUtility Tools &8⏷'
  small-caps-title: '&8⏷ &bSmall Caps &8⏷'
  gradient-maker-title: '&8⏷ &bGradient Maker &8⏷'
  color-palette-title: '&8⏷ &bColor Selector &8⏷'
  symbol-copier-title: '&8⏷ &bSymbol Copier &8⏷'
  enter-text: '&aPlease type your text in chat:'
  text-copied: '&aCopied to chat! Use Ctrl+A to select all:'
  conversion-complete: '&aConversion complete! Click the result to copy.'
  gradient-generated: '&aGradient generated! Copy from chat:'
  cancelled: '&cAction cancelled.'
  type-cancel: '&7Type &ccancel&7 to abort.'
```
