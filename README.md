# «Инструменты для тестирования мобильных приложений. Среда разработки»

## Решения
### Задание 1
* <a href="https://drive.google.com/file/d/1XObCcZi-bOhdhfPMBSr9diOm-HycpYSm/view?usp=sharing">logcat.txt</a> - лог-файл работы приложения, содержащий ошибки в работе приложения.


### Задание 2
* <a href="https://drive.google.com/file/d/1UKHbDyUGy32reM-zKBVNevZ3adrvGgi8/view?usp=sharing">Скриншот</a> терминала,
  с командой запуска стресс-теста Monkey.
* <a href="https://drive.google.com/file/d/1RqZpQMo-DAmkiUrJvB-oOvh68L1zaDjt/view?usp=sharing">logcatStress.txt</a> - логи приложения во время стресс-теста.


### Задание 3
* <a href="https://docs.google.com/document/d/1QqrIH-6KeD1HFTCfBKqTIVOreaPHg-xl5be8pMdlSxw/edit?usp=sharing">Crash Logs Conclusion</a> - заключение о причинах возникновения исключений.


## Что было сделано
### Задание 1
* Установлен тестовый [apk файл](https://drive.google.com/drive/folders/1qQv8KOGhWmwctOZy2evekI3ywb_dF-wi?usp=sharing) на android-устройство,
   с помощью [Android Debug Bridge (ADB)](https://developer.android.com/studio/releases/platform-tools)
* Проведен функциональный тест и вызвана ошибка.
* Сохранены логи приложения с отображенной ошибкой - <a href="https://drive.google.com/file/d/1XObCcZi-bOhdhfPMBSr9diOm-HycpYSm/view?usp=sharing">logcat.txt</a>.


### Задание 2
* Реализован скрипт запуска стресс-теста с использованием Monkey - <a href="https://drive.google.com/file/d/1UKHbDyUGy32reM-zKBVNevZ3adrvGgi8/view?usp=sharing">Скриншот</a> терминала,
  с командой запуска стресс-теста.
* Собраны логи работы приложения во время проведения стресс-теста - <a href="https://drive.google.com/file/d/1RqZpQMo-DAmkiUrJvB-oOvh68L1zaDjt/view?usp=sharing">logcatStress.txt</a>.


### Задание 3
* Изучены лог-файлы и определены наиболее вероятные причины возникновения исключений. Выводы отражены в
  <a href="https://docs.google.com/document/d/1QqrIH-6KeD1HFTCfBKqTIVOreaPHg-xl5be8pMdlSxw/edit?usp=sharing">Crash Logs Conclusion</a>.

  
## Описание Задания 1 

1. С помощью ADB-команды установите на устройство тестовый apk-файл. 
2. Запустите его логирование. 
3. Проведите небольшой функциональный тест приложения.
4. Постарайтесь вызвать какую-либо ошибку (вспоминаем best parctice).

Результат выполнения — ссылка на сохранённый log-файл с ошибкой. Если не удалось вызвать ошибку, то пришлите ссылку на скриншот терминала с логами приложения.


## Описание Задания 2

Вам дали задание провести стресс-тестирование предоставленного приложения. 

На основе [документации](https://developer.android.com/studio/test/other-testing-tools/monkey?hl=ru) составьте свой скрипт и сделайте так, чтобы запуск теста был только внутри приложения.


Результат выполнения — ссылка на скриншот терминала со скриптом запуска теста и файл с логами тестируемого приложения, если при тестировании оно выйдет из строя, или возникнет необработанное исключение.

## Описание Задания 3

1. Проведите анализ стектрейса ошибок. 
2. Оцените стек вызовов при возникновении ошибки.
3. Предположите, какой модуль приложения был затронут исходя из логов. 
4. Определите, какие действия или условия у пользователя могли его вызвать.

[Crash logs](https://drive.google.com/drive/folders/1h9HGWbhkRQzFsMlCdPJbJL93mR1tfdNf?usp=sharing).

Результат выполнения — ссылка на документ с вашими рассуждениями по представленным двум ошибкам. 
Для оценки задания важно ваше умение анализировать техническую информацию.
