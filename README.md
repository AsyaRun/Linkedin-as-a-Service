# LAaS — LinkedIn as a Service (Single-file landing)
Generated: 2025-08-09T08:47:59.419092Z

## Быстрый деплой (3 варианта)

### 1) Netlify (drag & drop)
1. Перейдите на https://app.netlify.com/drop
2. Перетащите ZIP-файл из этого набора
3. Получите готовую ссылку вида https://your-site.netlify.app
4. По желанию привяжите домен (Domains → Add)

### 2) Vercel (через Git)
1. Создайте репозиторий с файлами `index.html` и `styles.css`
2. Зайдите в https://vercel.com/new и подключите репозиторий
3. Проект задеплоится автоматически

### 3) GitHub Pages (бесплатно)
1. Создайте репозиторий и положите `index.html` и `styles.css` в корень
2. В Settings → Pages включите GitHub Pages для ветки `main`
3. Откройте выданный URL

## Куда вставлять форму
- Замените href у кнопок `Записаться на вводную сессию` на ссылку формы (Tally/Typeform/Google Form)
- Для аналитики добавьте в конец `index.html` ваш `<script>` Plausible/Umami/GA
