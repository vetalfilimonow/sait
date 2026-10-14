# THE CASH — метод від Content Papa

Статичний лендінг на GitHub Pages.

**Адреса:** https://vetalfilimonow.github.io/sait/

Джерело: HTML-віджет сайту vetalfilimonow.wixstudio.com/my-sitecash — вміст перенесено без змін.

## Структура
- `index.html` — уся сторінка: розмітка, стилі та скрипти в одному файлі
- `.nojekyll` — вимикає Jekyll, щоб HTML віддавався як є
- `img/` — фото автора та обкладинки бонусів

## Локальний запуск
```bash
python3 -m http.server 8000
```

## Фото
Посилання на картинки з Figma були тимчасовими й перестали працювати, тому зараз
замість фото показуються оформлені заглушки. Щоб повернути фото:

1. Поклади файли в папку `img/` (наприклад `img/author.jpg`).
2. В кінці `index.html`, у `CONFIG.images`, впиши шляхи:
   ```js
   images:{ author:'img/author.jpg', oracle:'img/oracle.jpg', toolkit:'img/toolkit.jpg', dividends:'img/dividends.jpg' },
   ```
