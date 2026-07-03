<div align="center">

# EasyEDA Themes

**Тёмные и светлые темы для редактора схем EasyEDA**

</div>

Расширение для EasyEDA, полностью переоформляющее интерфейс с помощью нескольких тёмных и светлых тем. Работает в браузере и в десктопном приложении. Темы описаны в JSON и применяются через CSS-инъекцию во время выполнения.

## ■ Возможности

- ❖ **Несколько тёмных тем** — One Dark, Darker, Monokai Pro, Dracula, Oceanic и другие
- ❖ **Светлые темы** — Light Owl и дополнительные светлые варианты
- ❖ **Выбор темы внутри приложения** — переключение тем через меню `Themer > Select Theme` на панели инструментов
- ❖ **Живой редактор CSS** — редактируйте и принудительно перезагружайте CSS без перемонтирования расширения
- ❖ **Управление через JSON** — добавляйте новые темы, редактируя `themes.json`

## ■ Стек

<div align="center">

| Компонент | Технология |
|-----------|------------|
| Расширение | JavaScript, EasyEDA Extension API |
| Стилизация | CSS (uploaded as .txt) |
| Темы | JSON color definitions |

</div>

## ■ Как это работает

```
1. Расширение загружает определения цветов из themes.json
2. Пользователь открывает меню Themer > Select Theme на панели инструментов и выбирает тему
3. Расширение инъектирует CSS во время выполнения, переоформляя весь интерфейс EasyEDA
4. Живой редактор CSS позволяет редактировать и принудительно перезагружать CSS без перемонтирования расширения
```

## ■ Скриншоты

<div align="center">

![One Dark](img/OneDark.png)

*Тема One Dark в EasyEDA*

![Dracula](img/Dracula.png)

*Тема Dracula в EasyEDA*

![Monokai Pro](img/Monokai_Pro.png)

*Тема Monokai Pro в EasyEDA*

</div>

## ■ Использование

```bash
# 1. Скачайте последний релиз:
#    https://github.com/pluttan/EasyEdaThemes/releases/
# 2. В EasyEDA: Advanced > Extensions > Extensions Settings
# 3. Load Extension > Select Files — выберите все файлы из папки extension/
# 4. Убедитесь, что в поле Extension ID указано "themes", затем загрузите
# 5. Используйте кнопку Themer > Select Theme на панели инструментов для выбора темы
```

## ■ Лицензия

MIT © [pluttan](https://github.com/pluttan)
