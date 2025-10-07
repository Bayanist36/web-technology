---
order: 1
title: Поурочный план веб-интенсива
---

### **Модуль 1 (6 ч) -- HTML-основы**

**Теория:**

-  Структура HTML-документа (\<!DOCTYPE html>, \<html>, \<head>, \<body>)

-  Семантические теги (\<header>, \<main>, \<section>, \<footer>)

-  Атрибуты (id, class, href, src)

-  Формы и элементы ввода (\<input>, \<textarea>, \<select>)

**Практика:**

-  Создать HTML-страницу с шапкой, основным блоком и футером

-  Добавить форму обратной связи

**Мини-проект:**\
«Визитка»: простая страница о себе с фото, контактами и формой.

**Ресурсы:**

-  [MDN HTML Guide](https://developer.mozilla.org/ru/docs/Web/HTML)

-  [HTML Academy -- интерактивные задания](https://htmlacademy.ru/courses/BasicHTML)

### **Модуль 2 (6 ч) -- CSS-базис**

**Теория:**

-  Подключение CSS (inline, internal, external)

-  Селекторы и псевдоклассы (:hover, :nth-child)

-  Flexbox и Grid

-  Основы адаптивности (media queries)

**Практика:**

-  Сверстать страницу из модуля 1 в стиле минимализма

-  Сделать адаптив под телефон

**Мини-проект:**\
Адаптивная визитка с красивым шрифтом и цветовой схемой.

**Ресурсы:**

-  [MDN CSS Guide](https://developer.mozilla.org/ru/docs/Web/CSS)

-  [Flexbox Froggy -- игра](https://flexboxfroggy.com/#ru)

### **Модуль 3 (6 ч) -- Основы JavaScript**

**Теория:**

-  Переменные (let, const)

-  Типы данных

-  Условия и циклы

-  Функции и работа с DOM (document.querySelector, addEventListener)

**Практика:**

-  Кнопка, меняющая цвет фона

-  Счётчик кликов

**Мини-проект:**\
Интерактивная страница с кнопкой «Показать/Скрыть текст».

**Ресурсы:**

-  [Learn JavaScript](https://learn.javascript.ru/) (главы 1–5)

-  [MDN JavaScript Basics](https://developer.mozilla.org/ru/docs/Learn/JavaScript/First_steps)

### **Модуль 4 (6 ч) -- htmx: быстрый интерактив**

**Теория:**

-  Установка htmx

-  Атрибуты: hx-get, hx-post, hx-trigger, hx-swap

-  AJAX-запросы без JS-кода

-  Интеграция с сервером

**Практика:**

-  Кнопка, подгружающая новый HTML-фрагмент

-  Список задач с удалением элемента без перезагрузки

**Мини-проект:**\
Чат-заготовка на htmx, где сообщения подгружаются с сервера.

**Ресурсы:**

-  [Официальный сайт htmx](https://htmx.org/)

-  [Введение в htmx (статья)](https://htmx.org/docs/)

### **Модуль 5 (6 ч) -- React: основы**

**Теория:**

-  Что такое React

-  JSX и компоненты

-  Пропсы и состояние (useState)

-  Рендеринг списков

**Практика:**

-  Список заметок с кнопкой добавления

-  Счётчик с кнопками +/-

**Мини-проект:**\
To-Do List на React (без бэка).

**Ресурсы:**

-  [React Docs](https://react.dev/)

-  [Scrimba React курс](https://scrimba.com/learn/learnreact)

### **Модуль 6 (6 ч) -- React: формы и эффекты**

**Теория:**

-  Управляемые формы

-  Хуки: useEffect

-  Работа с API (fetch)

**Практика:**

-  Форма регистрации с валидацией

-  Получение данных с публичного API

**Мини-проект:**\
Поиск картинок через API Unsplash.

**Ресурсы:**

-  [React Hooks Guide](https://react.dev/reference/react)

-  [JSONPlaceholder API](https://jsonplaceholder.typicode.com/)

### **Модуль 7 (6 ч) -- Node.js + Express**

**Теория:**

-  Установка Node.js, npm

-  Express: создание сервера

-  Маршруты GET, POST

-  Middleware

**Практика:**

-  Сервер, отдающий HTML

-  Обработка формы через POST

**Мини-проект:**\
Простой сервер обратной связи (форма -> письмо на email или запись в JSON).

**Ресурсы:**

-  [Express Docs](https://expressjs.com/ru/)

-  [Node.js Guide](https://nodejs.dev/)

### **Модуль 8 (6 ч) -- REST API**

**Теория:**

-  Принцип REST

-  CRUD-операции

-  Формат JSON

-  Подключение фронтенда к API

**Практика:**

-  API для задач

-  Подключение к To-Do на React

**Мини-проект:**\
React-приложение с серверным API.

**Ресурсы:**

-  [MDN REST API tutorial](https://developer.mozilla.org/ru/docs/Glossary/REST)

### **Модуль 9 (6 ч) -- MongoDB**

**Теория:**

-  NoSQL концепция

-  Подключение MongoDB Atlas

-  Модели и схемы (Mongoose)

**Практика:**

-  Коллекция задач

-  API, сохраняющее данные в БД

**Мини-проект:**\
To-Do List с сохранением данных в MongoDB.

**Ресурсы:**

-  [MongoDB Docs](https://www.mongodb.com/docs/)

-  [Mongoose Guide](https://mongoosejs.com/docs/)

### **Модуль 10 (6 ч) -- Аутентификация**

**Теория:**

-  JWT: принцип работы

-  Регистрация и вход

-  Защита маршрутов

**Практика:**

-  Создать регистрацию/логин

-  Ограничить доступ к API

**Мини-проект:**\
Личный кабинет с входом.

**Ресурсы:**

-  [JWT.io](http://JWT.io)

-  [Auth with Express](https://www.digitalocean.com/community/tutorials/nodejs-jwt-expressjs)

### **Модуль 11 (6 ч) -- Деплой**

**Теория:**

-  Vercel, Render, Railway

-  Подготовка фронта и бэка

-  Переменные окружения

**Практика:**

-  Залить React-приложение на Vercel

-  Залить сервер на Render

**Мини-проект:**\
Онлайн-версия твоего To-Do с базой и авторизацией.

**Ресурсы:**

-  [Vercel Deploy Guide](https://vercel.com/docs)

-  [Render Docs](https://render.com/docs)

### **Модуль 12 (6 ч) -- Итоговый проект**

**Задачи:**

-  Определить тему (чат, блог, таск-менеджер, каталог товаров)

-  Сделать фронтенд (React + при желании htmx для части страниц)

-  Сделать API (Node.js + Express)

-  Подключить MongoDB

-  Сделать авторизацию

-  Задеплоить

**Результат:**\
Готовое современное веб-приложение в портфолио.

Если хочешь, я могу в следующем шаге оформить это в **таблицу с чекбоксами** -- чтобы ты мог отмечать прогресс как на настоящем интенсиве и сразу видеть, что уже освоил.\
Хочешь, сделаем?