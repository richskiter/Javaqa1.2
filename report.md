# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

30.12.2020 - 31.12.2020 было проведено модульное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Некорректная валидация при вводе 19-символьного значения](https://github.com/richskiter/Javaqa1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Сервис генерации валидных номеров карт - [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* [Тест-кейсы](https://github.com/richskiter/Javaqa1.2/blob/master/test-cases.md)

В качестве тестовых данных использовались сгенерированные сервисом [Freeformatter](https://www.freeformatter.com/credit-card-number-generator-validator.html) номера кредитных карт:

VISA:
* 4262409643029398
* 4556424111052546
* 4331076538097322831

Visa Electron:
* 4913247752967328
* 4508366785615661
* 4175000997450102

MasterCard:
* 2221007067238778
* 2221000702274506
* 5127683473201002

InstaPayment:
* 6372764039668189
* 6397593532491836
* 6397473025228476

Discover:
* 6011340485214800651

American Express (AMEX):
* 374227646493335
* 343961076091502
* 372533950047357

Diners Club - International
* 36800564506393

Тестирование производилось в следующем окружении:
* Windows 10 x64
* openjdk version "11.0.9.1" 2020-11-04
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

