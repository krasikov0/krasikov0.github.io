# nk. — портфолио Nikolay Krasikov

Статический сайт: `index.html` (стили и анимации внутри) + папка `assets/`. Без сборки.

```
index.html     ← весь сайт
assets/img/    ← фото, скрины XINZ, аватар
assets/video/  ← 5 роликов ARBICUT и обложки
.nojekyll      ← служебный пустой файл для GitHub Pages
```

## Загрузка на GitHub Pages

1. github.com → **New repository**.
   - Назовёшь `<твой-ник>.github.io` → сайт будет по адресу `https://<твой-ник>.github.io`
   - Любое другое имя → `https://<твой-ник>.github.io/<имя>/`
2. В репозитории: **Add file → Upload files** → перетащи **всё содержимое этой папки**
   (`index.html`, `assets`, `.nojekyll`, `README.md`) — именно содержимое, не саму папку.
   `index.html` должен лежать в корне репозитория. → **Commit changes**.
   (Если `.nojekyll` не виден в Finder: Cmd+Shift+. показывает скрытые файлы.)
3. **Settings → Pages → Source: Deploy from a branch**, ветка `main`, папка `/ (root)` → **Save**.
4. Через 1–2 минуты сайт открыт.

## Языки
Английский по умолчанию, русский — кнопка RU в шапке или ссылка `?lang=ru`.
Русский текст лежит в разметке в атрибутах `data-ru="…"`.

## Посмотреть локально
```bash
python3 -m http.server 8790
```
http://localhost:8790
