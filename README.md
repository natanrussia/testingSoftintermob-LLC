# Тестовое задание на должность QA-инженера в Softintermob LLC:

Необходимо провести ручное тестирование **(manual testing)** проекта, который представлен в виде .apk файла “Test Project.apk”, используя следующие виды тестирования:
Функциональное тестирование
Позитивное тестирование
Негативное тестирование
Тестирование интерфейса пользователя **(ui testing)**
Тестирование удобства использования **(usability testing)**

**ТЗ по проекту:**
1. При запуске проекта должен появляться Splash Screen, после чего сразу основной экран приложения с кнопками функционала. 
2. Приложение должно работать только в портретной ориентации.
3. В приложении не должно быть рекламы на всех экранах и при любых действиях пользователя.
4. Весь контент в приложении должен отличаться наполнением во всех категориях.
5. Контент должен кэшироваться, чтобы при перемещении между страницами не происходило повторной загрузки контента.
6. Контент, кнопки подкатегорий и описания контента на детализированном экране должны скролиться.
7. При нажатии на иконку контента должен открываться детализированный экран данного модуля, в зависимости от категории контента.
8. При нажатии на кнопку Download на детализированном экране должен появиться алерт об успешном скачивании, а контент должен сохраняться.
9. Кнопка "Добавить в избранное" (Сердечко) должна функционировать, добавляя контент на экран Favorites и при активном статусе менять цвет как на основном экране, так и на детализированном.
10. На странице 'Sounds' должна быть возможность скачать и прослушать контент. Невозможно одновременное воспроизведение более чем одного звука.
11. При создании нового аддона в экране Mods Editor должна быть возможность редактировать изображение с помощью разных инструментов и добавлять разные настройки,  которые будут работать уже в игре Melon.
12. Созданные моды должны иметь возможность быть переименованы, удалены, а также должна быть функция ‘Download’ для их скачивания на экране Mods Editor.
13. При создании нового скина в экране Skin Maker должна быть возможность редактировать изображение с помощью разных инструментов.
14. Созданные скины должны быть переименованы, удалены, а также должна быть функция ‘Download’ для их скачивания на экране Skins Maker.

**Пример отчета об ошибке (баг-репорт):**
**Баг 1**
**Суть:** Не сохраняется сделанный выбор на экране Filters в меню Cheats; если изменить категорию в Filters, все элементы исчезают, пока пользователь снова не зайдет в меню и не выберет ту же категорию.
**Шаги для воспроизведения:**
Открыть приложение.
Тап Cheats.
Тап на Filters.
Тап на любой элемент (например, "Other").
Тап на любой элемент (например, "Parachute").
            Оценить результат.

**Actual result:** Не сохраняется выбор, сделанный в выпадающем меню Filter на экране Cheats=>Все меню=> Filter. Контент исчезает.
**Expected result:**  Выбор, сделанный в меню Filters, сохраняется после каждого изменения.
**Environment:** Все устройства (v15-16.6)
**Severity:** Major


### Чек-лист и результаты выполнения тестов

|ID|Описание проверки|Статус|Баг репорт|
|:---------|:------|:--------------|:-------------|
|1|При запуске приложения на экране появляется Splash Screen|||
||После запуска приложения основной экран приложения с кнопками функционала||
|2|Приложение должно работать только в портретной ориентации|||	
|3|В приложении не должно быть рекламы на всех экранах и при любых действиях пользователя|||	
|4|Весь контент в приложении должен отличаться наполнением во всех категориях|||
|5|Контент должен кэшироваться, чтобы при перемещении между страницами не происходило повторной загрузки контента|||
|6|Контент, кнопки подкатегорий и описания контента на детализированном экране должны скролиться|||
|7|При нажатии на иконку контента должен открываться детализированный экран данного модуля, в зависимости от категории контента|||
|8|При нажатии на кнопку Download на детализированном экране должен появиться алерт об успешном скачивании, а контент должен сохраняться|||
|9|Кнопка "Добавить в избранное" (Сердечко) должна функционировать, добавляя контент на экран Favorites и при активном статусе менять цвет как на основном экране, так и на детализированном|||
|10|На странице 'Sounds' должна быть возможность скачать и прослушать контент. Невозможно одновременное воспроизведение более чем одного звука.|||
|11|При создании нового аддона в экране Mods Editor должна быть возможность редактировать изображение с помощью разных инструментов и добавлять разные настройки, которые будут работать уже в игре Melon|||
|12|Созданные моды должны иметь возможность быть переименованы, удалены, а также должна быть функция ‘Download’ для их скачивания на экране Mods Editor|||
|13|При создании нового скина в экране Skin Maker должна быть возможность редактировать изображение с помощью разных инструментов.|||
|14|	Созданные скины должны быть переименованы, удалены, а также должна быть функция ‘Download’ для их скачивания на экране Skins Maker|||
|15||||
