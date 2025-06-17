# Travel Blog

Небольшой статический проект — пример блога о путешествиях с двумя страницами:  
- **index.html** — главная страница (список статей)  
- **article.html** — страница отдельной статьи  

Вёрстка выполнена по бэст-практикам:
- **Семантическая HTML5**  
- **БЭМ-методология**  
- **Адаптивный дизайн** (media-query для мобильных)  
- **Доступность (accessibility)**: alt-тексты, aria-атрибуты, фокусировка  
- **WebP + PNG-fallback** через `<picture>`  
- **Псевдоэлементы / псевдоклассы**  
- Чистая структура файлов и аккуратные отступы  

---

## Структура проекта

FrontFinal/
├── index.html — главная страница блога
├── article.html — страница статьи
├── style.css — стили для index.html
├── article.css — стили для article.html
└── img/ — изображения (WebP и PNG)
├── logo.png
├── logo.webp
├── travel-1.png
├── travel-1.webp
├── travel-2.png
├── travel-2.webp
├── author.png
└── author.webp

---

## Технологии

- HTML5  
- CSS3 (BEM, adaptive, pseudo-classes/elements)  
- WebP + PNG-fallback  
- Семантика и доступность  

---

## Запуск локально

1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/Evgeniy2001Poluhin/FrontFinal.git
   cd FrontFinal

   (Опционально) Запустить локальный HTTP-сервер:

bash
Копировать
Редактировать
python3 -m http.server 8000
Открыть в браузере:

http://localhost:8000/index.html

http://localhost:8000/article.html

Как пользоваться
index.html
Содержит заголовок блога и карточки статей.
Каждая карточка — картинка, заголовок, анонс и ссылка на полную статью.

article.html
Показывает полную статью с иллюстрациями, мета-данными (дата, автор) и сайдбаром с информацией об авторе.