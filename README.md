## Отчёт о тестировании функции вычисления бонусов.
### Краткое описание
Проведено негативное компонентное тестирование на соответствие требованиям по заданым условиям из Git репозитория (https://github.com/netology-code/javaqa-homeworks/tree/master/programming), программа написана в Intellij Idea на платформе Windows 8.1 64 разрядной ОС и Java 11. В результате тестирования выявлена ошибка в рассчете суммы бонусов.
Для рассчета был представлен тип double, вследствие чего возникла ошибка.

### Описание тестов
Было проведено негативное компонентное теститоравание отдельной функции вычесления для перевода средств на карту и функциональное тестирование на соответствие требованиям.

### Результаты
100% успешных тестов

Ссылки на баг-репорты

### Общие рекомендации
Заменить тип double на (какой-то другой, узнаю в следующей лекции), воизбежание данной ошибки.