# Отчёт о тестировании приложения Credit Card Number Validator
### Краткое описание

14.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1/6 часа.

В результате тестирования выявлены следующие дефекты:

* [19-значные номера карты VISA не проходят валидацию #1](https://github.com/EliseevG787/JAVAQA-1.2/issues/1)
* [15-значные номера карты AMEX не проходят валидацию #2](https://github.com/EliseevG787/JAVAQA-1.2/issues/2)
* [Некорректный вывод приложения при проверке валидного номера карты AMEX #3](https://github.com/EliseevG787/JAVAQA-1.2/issues/3)

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

[Генератор кредитных карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)

В качестве тестовых данных использовались данные сервисов [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html) и [creditcardgenerator.in](https://creditcardgenerator.in/card-generator/mir)

Валидные номера кредитных карт
VISA:
* 4556565161031333
* 4716811407532917
* 4716761446382601871

MasterCard:
* 2221002907949403
* 5228622879732929
* 2720999783502394

American Express (AMEX):
* 375385147402657
* 377762590775102
* 343111735934367

Diners Club - North America:
* 5479114277715850
* 5584984458139852
* 5589197239160098

MIR:
* 2201765937880801
* 2202729432479102
* 2200490245412075


Тестирование производилось в следующем окружении:

* Windows 10 LTSC X64

* openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
OpenJDK Client VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

* IntelliJ IDEA Community Edition

* [Credit Card Number Validator](https://github.com/EliseevG787/JAVAQA-1.2/blob/master/Main.java)
