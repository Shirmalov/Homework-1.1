# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.07.2020 - 11.07.2020 было проведено Функциональное тестирование приложения "Credit Card Number Validator"

На тестирование затрачено: 3 часа

В результате тестирования дефектов выявлено не было

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Checklist
* Bug Reports

В качестве тестовых данных использовались данные <https://www.freeformatter.com/credit-card-number-generator-validator.html>:

### VISA:
* 4485468531848351 - Result is OK
* 416020390117 - Result is FAIL
* 44854685318483$% - Result is FAIL
* 44853231794651qw - Result is FAIL
* 4539719055110841664 - Result is FAIL
### MasterCard:
* 5565395391636354 - Result is OK
* 272099819941 - Result is FAIL
* 52827645194047!@ - Result is FAIL
* 51767740858269sd - Result is FAIL
* 2221008733271821321 - Result is FAIL
### American Express (AMEX):
* 379875758579021 - Result is FAIL
* 346508939665126 - Result is FAIL
### Diners Club - Carte Blanche
* 30411389291306 - Result is FAIL
* 30157618115069 - Result is FAIL
### Diners Club - International
* 36105223693388 - Result is FAIL
* 36349872191308 - Result is FAIL

Тестирование производилось в следующем окружении:
* Windows 10 Pro 20H2, 64-Bit
* Jdk version "11.0.11" 64-Bit
* IntelliJ IDEA Community "2021.1.3" 64-Bit
