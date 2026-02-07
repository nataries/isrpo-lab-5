# Лабораторная работа №5. Введение в HTML
**ФИО**: Заставная Наталия Владимировна
**Группа**: ИСП-231
**Дата**: 30.01.2026
## Описание работы
В данной лабораторной работе создаётся проект для изучения основ HTML.
Вы настраиваете рабочую директорию, создаёте базовые файлы, подключаете Git и GitHub, а также 
подготавливаете HTML-файл для последующего изучения структуры веб-страницы.

Результатом выполнения лабораторной работы стал проект - визитка студента на языке HTML. Посмотреть сайт можно [по ссылке](webpageCard.html).
## Структура проекта
+ **index.html** — основной HTML-файл
+ **[README.md](#лабораторная-работа-5-введение-в-html)** — описание лабораторной работы
+ **img/** — скриншоты этапов выполнения лабораторной работы
+ **about.html** - Практическое задание 13 с семантической разметкой
+ **index2.html** - Примеры семантических тегов HTML (header, nav, main, section, article, footer)
+ **webpageCard.html** - визитная карточка студента
---

## Теги в HTML
Структура парного тега:
**<тег>тело<\/тег>**

*Пример:*
```html
<h1>Это заголовок</h1>
```

## Базовые HTML-теги
### Примеры:
```html
<h2>Заголовок</h2>
<p>Абзац текста</p>
<strong>Жирный</strong>
<em>Курсив</em>
<hr>
<a href="https://example.com">Ссылка</a>
<img src="example.jpg" alt="Описание">
```
## Списки в HTML
1. Нумерованный список 
```html
<ol>
      <li>Первый пункт</li>
      <li>Второй пункт</li>
      <li>Третий пункт</li>
</ol>
```
2. Маркированный список
```html
<ul>
      <li>Элемент списка</li>
      <li>Ещё один элемент</li>
</ul>
```
3. Вложенные списки
```html
<ul>
    <li>Пункт 1
        <ol>
          <li>Вложенный 1</li>
          <li>Вложенный 2</li>
        </ol>
    </li>
</ul>
```
## Атрибуты HTML-элементов
1. Примеры глобальных атрибутов
```html
<p id="intro">Это абзац с id</p>
<p class="highLight">Выделенный текст</p>
<p class="highLight big-text spaced">...</p>
<span title="Это подсказка">Наведи на меня</span>
<p style="color: blue; font-size: 20px">Синий текст</p>
```
2. Примеры специальных (для конкретных тегов)
```html
<p><a href="https://google.com">Google</a></p>
<img src="#" alt="Котик" />
<img src="#" width="200" height="150" />
<p><a href="https://yandex.ru" target="_blank">Открыть в новой вкладке</a></p>
<p>
    <input type="number" />
    <input type="password" />
    <input type="email" />
</p>
<p><input type="text" placeholder="Введите имя" /></p>
```
## Таблицы в HTML
Таблица состоит из `<table>` (сама таблица), `<tr>`(строка), `<td>`(ячейка), `<th>`(заголовок столбца)

```html
<table border="1">
      <tr>
        <th>Имя</th>
        <th>Возраст</th>
      </tr>
      <tr>
        <td>Алексей</td>
        <td>21</td>
      </tr>
      <tr>
        <td>Мария</td>
        <td>19</td>
      </tr>
    </table>
```
##  Формы и элементы форм (form, input, textarea, select)
Ниже приведён код формы:

```html
<form>
      <label for="username">Имя:</label>
      <input id="username" type="text" placeholder="Введите имя:" />
      <br /><br />
      <label for="email">Email:</label>
      <input id="email" type="email" placeholder="example@mail.com" />
      <br /><br />
      <label for="city">Город</label>
      <select id="city">
        <option>Волгоград</option>
        <option>Волжский</option>
        <option>Камышин</option>
      </select>
      <br><br>
      <label for="message">Сообщение:</label>
      <textarea id="message" rows="4" placeholder="Напишите текст..."></textarea>
      <br><br>
      <button type="submit">Отправить</button>
    </form>
```
## Семантические теги HTML (header, nav, main, section, article, footer)

1. Шапка сайта или раздела
```html
<header>
    <h1>Мой сайт</h1>
</header>
```
2. Навигация по сайту
```html
<nav>
    <a href="#">Главная</a>
    <a href="#">Обо мне</a>
</nav>
```
3. Основное содержание страницы
```html
<main>
    <h2>Добро пожаловать!</h2>
</main>
```
4. Логический раздел
```html
<section>
    <p>используется для отдельных частей страницы по смыслу</p>
</section>
```
5.  Самостоятельный блок контента
```html
<article>
    <p>Самостоятельный блок контента</p>
</article>
```
6. Подвал сайта
```html
<footer>
    <p>@2026 |Zastavnaya Nataliya |ISP-231</p>
</footer>
```