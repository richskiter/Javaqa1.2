# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

30.12.2020 - 31.12.2020 было проведено модульное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Некорректная валидация при вводе 19-символьного значения](https://github.com/richskiter/Javaqa1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Тест-кейсы](https://github.com/richskiter/Javaqa1.2/blob/master/test-cases.md)
* [Баг-репорт](https://github.com/richskiter/Javaqa1.2/issues/1)

В качестве тестовых данных использовались сгенерированные сервисом [Freeformatter](https://www.freeformatter.com/credit-card-number-generator-validator.html) номера кредитных карт:

VISA:
* 4331076538097322831

MasterCard:
* 5424291943874703

Maestro:
* 6762102220391337

Тестирование производилось в следующем окружении:
* Windows 10 x64
* openjdk version "11.0.9.1" 2020-11-04
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

