# XenForo-2.0-Russian-Documentation
Русский перевод документации XenForo 2.0

**Переводчик:** Нет тут ничего такого занятного, мне просто захотелось перевести документацию XF2. Я уже более 3 месяцев использую XenForo 2.0 и за это время уже достаточно в ней разобрался и свыкся с её работой, но все же остаются темные моменты или моменты которые к сожалнию не запомнились, в следствие чего приходится обращатся за помощью к документации, каждый раз переводя тот или иной участок текста заново. Мне это немного надоело я решил выполнить перевод и выложить его в свободный доступ. Как говорится, "просто захотелось", но просто не бывает :). 

Я не так хорошо знаю английский, а если быть на чистоту, то я в нем полный "чайник" и перевод выполняется при помощи Google переводчика, а результат приводится вручную уже к более читабельному виду. Так что буду не против вашего вмешательства в перевод путем отправки запросов и пулреквестов.

**Приветствуются правки ошибок и описаний, а так же дополнение информации.**

----------------

**Состояние перевода:**

|Общее состояние					|82,5%	|Состояние перевода	    |
|:--								|:--	|:--					|
|Начало работы						|100%	|Завершено.		        |
|Структура плагина					|100%	|Завершено. 			|
|Инструменты разработки				|100%	|Завершено.				|
|Общие понятия						|98%	|Обработка перевода.	|
|Основы маршрутизации				|98%	|Обработка перевода.	|
|Основы контроллера					|99%	|Уточнение деталей. 	|
|Сущности, Поисковики и Репозитории	|1%		|Английская версия.		|
|Управление схемой					|99%	|Уточнение деталей.		|
|Давайте построим плагин			|16.5%	|Английская версия.		|
|Проектирование стилей				|98%	|Обработка перевода.	|
|Приложение: Scotch Box				|98%	|Обработка перевода.	|


----------------

**Содержание**
* [Начало работы](/documentation/GettingStarted.md#part0)
  * [Что нового для разработчиков](/documentation/GettingStarted.md#part1)
  * [Начало работы](/documentation/GettingStarted.md#part2)
  * [Загрузка XF 2.0](/documentation/GettingStarted.md#part3)
  * [Системные требования XF 2.0](/documentation/GettingStarted.md#part4)
  * [Настройка локального сервера](/documentation/GettingStarted.md#part5)
    * [Предварительно построенная виртуальная машина](/documentation/GettingStarted.md#part6)
    * [Готовые сборки](/documentation/GettingStarted.md#part7)
  * [Загрузка](/documentation/GettingStarted.md#part8)
  * [Создание src/config.php](/documentation/GettingStarted.md#part9)
  * [Замечание по правам доступа к файлам](/documentation/GettingStarted.md#part10)
  * [Установка](/documentation/GettingStarted.md#part11)
  * [Переустановка](/documentation/GettingStarted.md#part12)
  * [Провека целостности файлов](/documentation/GettingStarted.md#part13)
  * [Команды управления плагинами](/documentation/GettingStarted.md#part14)
    * [Установка](/documentation/GettingStarted.md#part15)
    * [Обновление](/documentation/GettingStarted.md#part16)
    * [Перестроение](/documentation/GettingStarted.md#part17)
    * [Удаление](/documentation/GettingStarted.md#part18)
* [Структура плагина](/documentation/AddOnStructure.md#part0)
  * [Идентификаторы плагина и дополнительные надстройки](/documentation/AddOnStructure.md#part1)
  * [Рекомендуемый формат версии](/documentation/AddOnStructure.md#part2)
  * [Рекомендации к идентификатору версии](/documentation/AddOnStructure.md#part3)
  * [Основные файлы и директории плагина](/documentation/AddOnStructure.md#part4)
    * [Файл addon.json](/documentation/AddOnStructure.md#part5)
    * [Файл hashes.json](/documentation/AddOnStructure.md#part6)
    * [Файл Setup.php](/documentation/AddOnStructure.md#part7)
    * [Директория _data](/documentation/AddOnStructure.md#part8)
    * [Директория _output](/documentation/AddOnStructure.md#part9)
  * [Класс установки](/documentation/AddOnStructure.md#part10)
* [Инструменты разработки](/documentation/DevelopmentTools.md#part0)
  * [Режим отладки](/documentation/DevelopmentTools.md#part1)
  * [Включение режима разработки](/documentation/DevelopmentTools.md#part2)
  * [Команды разработки](/documentation/DevelopmentTools.md#part3)
  * [Дополнительные команды плагинов](/documentation/DevelopmentTools.md#part4)
    * [Создание нового плагина](/documentation/DevelopmentTools.md#part5)
    * [Экспорт .XML файлов _data](/documentation/DevelopmentTools.md#part6)
    * [Повышение версии плагина](/documentation/DevelopmentTools.md#part7)
    * [Синхронизация addon.json с базой данных](/documentation/DevelopmentTools.md#part8)
    * [Проверка файла addon.json](/documentation/DevelopmentTools.md#part9)
    * [Запустить отдельный шаг установки](/documentation/DevelopmentTools.md#part10)
      * [Запустить шаг установки](/documentation/DevelopmentTools.md#part11)
      * [Запустить шаг обновления](/documentation/DevelopmentTools.md#part12)
      * [Запустить шаг удаления](/documentation/DevelopmentTools.md#part13)
  * [Выпуск сборки плагина](/documentation/DevelopmentTools.md#part14)
    * [Расширеный процесс сборки](/documentation/DevelopmentTools.md#part15)
  * [Команды разработки](/documentation/DevelopmentTools.md#part16)
    * [Импорт вывода разработки](/documentation/DevelopmentTools.md#part17)
    * [Экспорт вывода разработки](/documentation/DevelopmentTools.md#part18)
  * [Отладка кода](/documentation/DevelopmentTools.md#part19)
    * [Отладка переменной](/documentation/DevelopmentTools.md#part20)
* [Общие понятия](/documentation/GeneralConcepts.md#part0)
  * [Компоненты поставщика](/documentation/GeneralConcepts.md#part1)
  * [Интегрированная среда разработки (IDE)](/documentation/GeneralConcepts.md#part2)
  * [АвтоЗагрузчик](/documentation/GeneralConcepts.md#part3)
  * [Пространства имён](/documentation/GeneralConcepts.md#part4)
  * [Короткие имена классов](/documentation/GeneralConcepts.md#part5)
  * [Расширение классов](/documentation/GeneralConcepts.md#part6)
  * [Типовые подсказки](/documentation/GeneralConcepts.md#part7)
* [Основы маршрутизации](/documentation/RoutingBasics.md#part0)
  * [Простой пример](/documentation/RoutingBasics.md#part1)
    * [Префикс маршрута](/documentation/RoutingBasics.md#part2)
    * [Раздел контекста](/documentation/RoutingBasics.md#part3)
    * [Контроллер](/documentation/RoutingBasics.md#part4)
    * [Экшен контроллера](/documentation/RoutingBasics.md#part5)
    * [Более продвинутый пример (форматы маршрута)](/documentation/RoutingBasics.md#part6)
    * [Параметры маршрута](/documentation/RoutingBasics.md#part7)
    * [Суб-имена](/documentation/RoutingBasics.md#part8)
* [Основы контроллера](/documentation/ControllerBasics.md#part0)
  * [Ответ "Просмотр"](/documentation/ControllerBasics.md#part1)
  * [Ответ "Перенаправление"](/documentation/ControllerBasics.md#part2)
  * [Ответ "Ошибка"](/documentation/ControllerBasics.md#part3)
  * [Ответ "Сообщение"](/documentation/ControllerBasics.md#part4)
  * [Ответ "Исключение"](/documentation/ControllerBasics.md#part5)
  * [Ответ "Перенаправление маршрута"](/documentation/ControllerBasics.md#part6)
  * [Изменение ответа на действие контроллера (правильно)](/documentation/ControllerBasics.md#part7)
* [Сущности, Поисковики и Репозитории](/documentation/EntitiesFindersAndRepositories.md#part0)
  * [Поисковики (Finder)](/documentation/EntitiesFindersAndRepositories.md#part1)
    * [Метод where](/documentation/EntitiesFindersAndRepositories.md#part2)
    * [Метод whereOr](/documentation/EntitiesFindersAndRepositories.md#part3)
    * [Метод with](/documentation/EntitiesFindersAndRepositories.md#part4)
    * [Метод order](/documentation/EntitiesFindersAndRepositories.md#part5)
    * [Метод limitByPage](/documentation/EntitiesFindersAndRepositories.md#part6)
    * [Метод limit](/documentation/EntitiesFindersAndRepositories.md#part7)
    * [Метод getQuery](/documentation/EntitiesFindersAndRepositories.md#part8)
    * [Расширение методов поисковика](/documentation/EntitiesFindersAndRepositories.md#part9)
  * [Система сущностей (Entity)](/documentation/EntitiesFindersAndRepositories.md#part10)
    * [Структура сущностей](/documentation/EntitiesFindersAndRepositories.md#part11)
      * [Таблица](/documentation/EntitiesFindersAndRepositories.md#part12)
      * [Короткое имя](/documentation/EntitiesFindersAndRepositories.md#part13)
      * [Тип контента](/documentation/EntitiesFindersAndRepositories.md#part14)
      * [Основной ключ](/documentation/EntitiesFindersAndRepositories.md#part15)
      * [Колонки](/documentation/EntitiesFindersAndRepositories.md#part16)
      * [Поведения](/documentation/EntitiesFindersAndRepositories.md#part17)
      * [Геттеры](/documentation/EntitiesFindersAndRepositories.md#part18)
      * [Связи](/documentation/EntitiesFindersAndRepositories.md#part19)
      * [Опции](/documentation/EntitiesFindersAndRepositories.md#part20)
    * [Жизненный цикл сущностей](/documentation/EntitiesFindersAndRepositories.md#part21)
  * [Репозитории (Repository)](/documentation/EntitiesFindersAndRepositories.md#part22)
* [Управление схемой](/documentation/SchemaManagement.md#part0)
  * [Адаптер базы данных](/documentation/SchemaManagement.md#part1)
  * [Управление схемой](/documentation/SchemaManagement.md#part2)
* [Давайте построим плагин](/documentation/LetsBuildAnAddOn.md#part0)
  * [Создание плагина](/documentation/LetsBuildAnAddOn.md#part1)
  * [Создание класса установки](/documentation/LetsBuildAnAddOn.md#part2)
  * [Расширение сущности XF:Forum](/documentation/LetsBuildAnAddOn.md#part3)
  * [Расширение сущности XF:Thread](/documentation/LetsBuildAnAddOn.md#part4)
  * [Создание новой сущности](/documentation/LetsBuildAnAddOn.md#part5)
  * [Изменение формы редактирования форума](/documentation/LetsBuildAnAddOn.md#part6)
  * [Расширение процесса сохранения XF:Forum](/documentation/LetsBuildAnAddOn.md#part7)
  * [Настройка потока, которая будет отображаться автоматически](/documentation/LetsBuildAnAddOn.md#part8)
  * [Создание страницы портала](/documentation/LetsBuildAnAddOn.md#part9)
  * [Создание пункта навигации](/documentation/LetsBuildAnAddOn.md#part10)
  * [Manually featuring (or unfeaturing) threads](/documentation/LetsBuildAnAddOn.md#part11)
  * [Улучшение страницы портала](/documentation/LetsBuildAnAddOn.md#part12)
  * [Создание разрешений и оптимизация](/documentation/LetsBuildAnAddOn.md#part13)
  * [Создание некоторых параметров](/documentation/LetsBuildAnAddOn.md#part14)
  * [Не возможно изменить видимость](/documentation/LetsBuildAnAddOn.md#part15)
  * [Последние штрихи](/documentation/LetsBuildAnAddOn.md#part16)
  * [Сборка плагина](/documentation/LetsBuildAnAddOn.md#part17)
* [Проектирование стилей](/documentation/DesigningStyles.md#part0)
  * [Включение режима дизайнера](/documentation/DesigningStyles.md#part1)
  * [Включение режима дизайнера для стиля](/documentation/DesigningStyles.md#part2)
  * [Отключение режима дизайнера для стиля](/documentation/DesigningStyles.md#part3)
  * [Что выводится и где?](/documentation/DesigningStyles.md#part4)
    * [Шаблоны](/documentation/DesigningStyles.md#part5)
    * [Группы и параметры стилей](/documentation/DesigningStyles.md#part6)
  * [Изменение конкретного шаблона](/documentation/DesigningStyles.md#part7)
  * [Другие полезные команды](/documentation/DesigningStyles.md#part8)
    * [Экспорт в базу данных](/documentation/DesigningStyles.md#part9)
    * [Импорт в файловую систему](/documentation/DesigningStyles.md#part10)
    * [Синхронизация шаблонов](/documentation/DesigningStyles.md#part11)
    * [Обратный шаблон](/documentation/AppendixScotchBox.md#part12)
* [Приложение: Scotch Box](/documentation/AppendixScotchBox.md#part0)
  * [Установка Scotch Box](/documentation/AppendixScotchBox.md#part1)
  * [Куда идут файлы?](/documentation/AppendixScotchBox.md#part2)
  * [Остановка и перезапуск сервера](/documentation/AppendixScotchBox.md#part3)
  * [Официальная документация](/documentation/AppendixScotchBox.md#part4)
  * [Scotch Box Профессионал](/documentation/AppendixScotchBox.md#part5)
