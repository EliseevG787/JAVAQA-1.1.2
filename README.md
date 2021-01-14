# Отчёт о тестировании приложения Credit Card Number Validator
### Краткое описание

14.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1/6 часа.

В результате тестирования выявлены следующие дефекты:

* [Некорректный вывод приложения при проверке валидного номера карты VISA #1](https://github.com/EliseevG787/JAVAQA-1.2/issues/1)
* [Дефект #2](https://github.com/EliseevG787/JAVAQA-1.2/issues/2)
* [Дефект #3](https://github.com/EliseevG787/JAVAQA-1.2/issues/3)

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

[Генератор кредитных карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)

В качестве тестовых данных использовались данные сервиса [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Валидные номера кредитных карт
VISA:
* 4556565161031333
* 4716811407532917
* 4716761446382601871
* 4485790440158623273

MasterCard:
* 2221002907949403
* 5228622879732929
* 2720999783502394
* 5424148357249824

American Express (AMEX):
* 375385147402657
* 377762590775102
* 343111735934367
* 377956332052594

Diners Club - North America:
* 5479114277715850
* 5584984458139852
* 5589197239160098
* 5452025482247862

Maestro:
* 6304613161564950
* 6761662108939631
* 6762091059801674
* 0604245498772806


Тестирование производилось в следующем окружении:

* Windows 10 LTSC X64

* openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
OpenJDK Client VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

* IntelliJ IDEA Community Edition

* [Credit Card Number Validator](https://github.com/EliseevG787/JAVAQA-1.2/blob/master/Main.java)
