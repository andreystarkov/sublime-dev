## Sublime 3 Front End Build

Наш билд Sublime Text 3 для фронт-энда, с небольшой оглядкой на фул-стак.

### Цветовые схемы

Можно менять через плагины Themr/Schemr.

<p align="center">
<img src="Build/sublime-seti.jpg" width="100%">
<div align="left"><i>Seti UI</i></div>
</p>

<p align="center">
<img src="Build/sublime-one.jpg" width="100%">
<div align="left"><i>One Dark (типа Atom)</i></div>
</p>

### Для работы SublimeLinter

Для отлова ошибок надо установить пару node модулей:

```
npm install -g csslint
npm install -g jshint
```

В файле Preferences.sublime-settings указать пути к node

```json
"sublimelinter_executable_map":
{
    "javascript":"C:\\Program Files\\nodejs\\node.exe",
    "jslint":"C:\\Program Files\\nodejs\\node.exe",
    "css":"C:\\Program Files\\nodejs\\node.exe"
}
```

### Хоткеи
* 1. [Хоткеи специфические](Build/hot-keys.pdf)
* 2. [Справочник по всем](Build/sublime_text_keyboard_shortcuts.pdf)



































