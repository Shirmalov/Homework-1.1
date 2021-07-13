# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.07.2020 - 11.07.2020 было проведено Функциональное тестирование приложения "Credit Card Number Validator"

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Checklist
* Bug Reports

В качестве тестовых данных использовались данные <https://www.freeformatter.com/credit-card-number-generator-validator.html>:

### VISA:
* 4556883704923456 - Result is OK
### MasterCard:
* 2221006486297670 - Result is OK
### Discover:
* 6011518788131113 - Result is OK
### JCB:
* 3544932387938021 - Result is OK
### Diners Club - North America:
* 5448138985449344 - Result is OK
### Maestro:
* 6759855262222158 - Result is OK
### Visa Electron:
* 4026385406606456 - Result is OK
### InstaPayment:
* 6383232500990679 - Result is OK

### Diners Club - Carte Blanche:
* 30246899485067 - Result is FAIL
### Diners Club - International:
* 36947957268469 - Result is FAIL





Тестирование производилось в следующем окружении:
* Windows 10 Pro 20H2, 64-Bit
* Jdk version "11.0.11" 64-Bit
* IntelliJ IDEA Community "2021.1.3" 64-Bit
