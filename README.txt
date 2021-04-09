# Отчёт о тестировании Credit Card Number Validator

## Программа проверяет валидность введенных данных банковских карт.

7.04.2021 было проведено полуавтоматизированное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0:30

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Создать новый проект по тестированию на IntelliJ IDEA 2020.3.3 
* Вставить код для тестирования https://github.com/netology-code/javaqa-homeworks/tree/master/intro
* Ввести номера банковских карт из тестовых данных https://fakepersongenerator.com/credit-card-generator
* Запустить проверку 

В качестве тестовых данных использовались данные https://fakepersongenerator.com/credit-card-generator:
* Номер карты Mastercard 5371901021237416
* Номер карты Visa 4054197654660435
* Номер карты Мaestro 639002459008836851

Ожидаемый результат, соответственно:
* Result is OK
* Result is OK
* Result is OK

Фактический результат, соответственно: 
* Result is OK
* Result is FAIL
* Result is FAIL

Тестирование производилось в следующем окружении:
* Windows 10, x64
* javac 11.0.10

## Скриншоты
