<div align="center">

# EasyEDA Themes

**Dark and light themes for the EasyEDA circuit editor**

</div>

An EasyEDA extension that overhauls the entire UI with multiple dark and light themes. Works in the browser and the standalone app. Themes are defined in JSON and applied via runtime CSS injection.

## ■ Features

- ❖ **Multiple dark themes** — One Dark, Darker, Monokai Pro, Dracula, Oceanic, and more
- ❖ **Light themes** — Light Owl and additional light variants
- ❖ **In-app theme picker** — switch themes from the `Themer > Select Theme` toolbar menu
- ❖ **Live CSS editor** — edit and force-reload CSS without remounting the extension
- ❖ **JSON-driven** — add new themes by editing `themes.json`

## ■ Stack

<div align="center">

| Component | Technology |
|-----------|------------|
| Extension | JavaScript, EasyEDA Extension API |
| Styling | CSS (uploaded as .txt) |
| Themes | JSON color definitions |

</div>

## ■ How It Works

```
1. Extension loads color definitions from themes.json
2. User opens the Themer > Select Theme toolbar menu and picks a theme
3. The extension injects CSS at runtime to restyle the entire EasyEDA UI
4. The Live CSS editor allows editing and force-reloading CSS without remounting the extension
```

## ■ Screenshots

<div align="center">

![One Dark](img/OneDark.png)

*One Dark theme applied to EasyEDA*

![Dracula](img/Dracula.png)

*Dracula theme applied to EasyEDA*

![Monokai Pro](img/Monokai_Pro.png)

*Monokai Pro theme applied to EasyEDA*

</div>

## ■ Usage

```bash
# 1. Download the latest release:
#    https://github.com/pluttan/EasyEdaThemes/releases/
# 2. In EasyEDA: Advanced > Extensions > Extensions Settings
# 3. Load Extension > Select Files — select all files from the extension/ folder
# 4. Make sure the Extension ID field says "themes", then load
# 5. Use the Themer > Select Theme toolbar button to pick a theme
```

## ■ License

MIT © [pluttan](https://github.com/pluttan)
