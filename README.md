# Ug-khan - Code Spell Checker

Ug-khan dictionary extension for VS Code.

## usage

Adding `ug-khan` to the `cSpell.language` setting, will enable the Ug_khan dictionary.
Example using both English and Ug-khan dictionaries:

```javascript
"cSpell.language": "en,ug-khan",
```

- vscode 的设置文件中搜索 cSpell.language 语言选择或者填写 ug-khan 即可激活插件的校对功能
- 可以在 vscode 的配置文件 settings.json 中直接写入以上配置也能激活校对，二者作用一样
- 默认文档中的检查词汇数量约束 1000 个词，vscode 配置里搜索 code spell checker 关键字，往里面找对应设置并把数量调大到自己想要的数字，为了性能考虑建议控制在一万个单词之内
- 此插件作为 `Code Spell Checker` 插件的一个词库插件，所有功能以 `Code Spell Checker` 提供的为准，所有配置，自定义，扩展请看 插件`Code Spell Checker`和它的文档。

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

Adding `ug-khan` to the `cSpell.language` setting, will enable the Ug_khan dictionary.
Example using both English and Ug-khan dictionaries:

```javascript
"cSpell.language": "en,ug-khan",
```

## Requirements

This extension will automatically include [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) extension.
