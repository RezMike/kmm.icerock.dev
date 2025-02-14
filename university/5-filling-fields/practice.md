---
sidebar_position: 5
---

# Практическое задание
Необходимо добавить новый функционал в ваше приложение, готовое после 4ого блока.
Предлагаем сделать возможность создавать issue к репозиторию, с экрана детальной информации.

Во время работы над практическим заданием настоятельно рекомендуем обращаться к разделу [Памятки для разработчика](../memos/function)

## Функциональные требования
1. Добавьте в ваше Github-приложение новый экран - создание issue, используйте. Экран должен содержать:
    - поле ввода `title`
    - поле ввода `body`
    - scroll для маленьких экранов
    - кнопка `Create issue`
1. Отображать пользователю ошибки валидации от сервера
1. Переход на новый экран создания issue должен происходить по кнопке, с экрана просмотра детальной информации о репозитории.

## Технические требования
1. Использовать `moko-fields` для реализации всех форм ввода
1. Использовать `moko-errors` для отображения пользователю информации об ошибке
1. Использовать `moko-network` для обработки ошибок валидации от сервера
1. Реализовать кастомный парсер ошибок валидации, для обработки ответа 

## Материалы
1. [GitHub Issues API](https://docs.github.com/en/rest/issues/issues#about-the-issues-api)
1. [422 Unprocessable Entity response](https://docs.github.com/en/rest/overview/resources-in-the-rest-api#client-errors)
1. [Дизайн Android](https://www.figma.com/file/Mh3ga5XAzyJNCY87NBp01G/Git_test-Android?node-id=4426%3A4427)
1. [Дизайн iOS](https://www.figma.com/file/XmpoCqkdWTGb2NGdR2bgiQ/Git_test-iOS?node-id=1532%3A1724)
