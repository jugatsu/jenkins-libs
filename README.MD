## Глоссарий

* Конвейер - последотваельность стадии и шагов
* Библиотеки - комплект подготовленных вложенных конвейеров
* Фукции библиотек и конвейеров - общий модуль функций повторного использования 


## Шаги выполнения лабораторной

| Шаг    | Требование к шагу |
| ------ | ------   |
| Синхронизация хранилища                         | Обязательно   |
| Создание тестового контура                      | Обязательно   | 
| Обновление тестового контура тестового контура  | Обязательно   | 
| Синтаксическая проверка кода                    | Обязательно   | 
| Дымовое тестирование                            | Обязательно   | 
| Функциональное тестирование                     | Обязательно   | 
| Сборка поставки                                 | Обязательно   |  
| Публикация отчетов                              | Обязательно   |  
| Отправка письма                                 | Обязательно   |  
| Призовой шаг - отправка сообщения в телегу      | Обязательно   |  

Порядок кодирования

* кодируем шаг в библиотеке
* вызваем шаг в репозитории конфы 
* внутри шага библиотеки есть функции
* функции внутри шага библиотеки также можно вызывать в репозитории конфы

## Включение библиотек

* подключение репозитория библиотек - включаем Global PipelineLibs (штатный плагин)