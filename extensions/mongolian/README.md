# Mongolian - Code Spell Checker

Mongolian dictionary extension for VS Code.

Imports the Mongolian spell checking dictionary for [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker).

## Installation

After this extension is installed, it is necessary to tell the spell checker to use it.

### Enable Dictionary

Commands (use `F1` or _View -> Command Palette..._):

- `F1` `Show Spell Checker Configuration Info`
- Select the `Language` tab.
- Enable the language Globally or in just the Workspace.

### Disable Dictionary

Commands (use `F1` or _View -> Command Palette..._):

- `F1` `Show Spell Checker Configuration Info`
- Select the `Language` tab.
- Disable the language Globally or in just the Workspace.

### Manual Settings

This is done with the `language` setting.

_Preferences_ -> _Settings_

Adding `mn-mn` to the `cSpell.language` setting, will enable the Mongolian dictionary.
Example using both English and Mongolian dictionaries:

```javascript
"cSpell.language": "en,mn-mn",
```

## Requirements

This extension will automatically include [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) extension.

## Contributors

_Language_ - [Battseren Badral](https://github.com/btseee)

<!--- @@inject: ../../static/footer.md --->

<!--- 
cspell:words Battseren Badral
--->

