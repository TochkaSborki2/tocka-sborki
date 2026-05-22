# Точка Сборки — Landing Page

Метод Евгения Королёва. Life OS за 8 недель.

## Развёртывание на Vercel

### Вариант 1: Через GitHub (рекомендуется)

1. Создайте репозиторий на GitHub: `https://github.com/new`
2. Назовите его `tocka-sborki`
3. После создания выполните:

```bash
cd ~/vercel-projects/tocka-sborki
git remote add origin https://github.com/YOUR_USERNAME/tocka-sborki.git
git branch -M main
git push -u origin main
```

4. Перейдите на `https://vercel.com/new` и авторизуйтесь
5. Нажмите "Import Git Repository"
6. Вставьте URL вашего репо: `https://github.com/YOUR_USERNAME/tocka-sborki.git`
7. Нажмите "Import"
8. Vercel автоматически развернёт проект

### Вариант 2: Через веб-интерфейс Vercel (без GitHub)

1. Перейдите на `https://vercel.com/new/static`
2. Загрузите файл `index.html`
3. Нажмите Deploy

## Ссылка на развёртанный проект

После развертывания Vercel дастдомен вида:
- `tocka-sborki.vercel.app` или
- Ваш кастомный домен (если настроили)

## Структура проекта

```
tocka-sborki/
├── index.html       # Основная страница лендинга
├── vercel.json      # Конфигурация для Vercel
└── README.md        # Этот файл
```

## Обновление лендинга

Если захочешь обновить контент:

1. Отредактируй `index.html`
2. Закоммить изменения:
   ```bash
   cd ~/vercel-projects/tocka-sborki
   git add index.html
   git commit -m "Update landing page content"
   git push
   ```
3. Vercel автоматически пересоберёт и развернёт проект

---

Готово к развертыванию! ✨
