# Отчёт о тестировании Money Transfer

## Краткое описание

04.04.2020 было проведено функциональное приёмочное тестирование приложения Money Transfer.

На тестирование затрачено: 0,5 часа

В результате тестирования выявлены следующие дефекты:
* [Некорректный тип переменных account, order и total](https://github.com/nmoraru/javaqa_2.1/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Java-код приложения Money Transfer](https://github.com/nmoraru/javaqa_2.1/blob/master/src/Solution.java)

В качестве тестовых данных использовались данные:
* account = 2_000_000_000 : OK
* order = 500_000_000 : OK

Тестирование производилось в следующем окружении:
* Windows 10 Pro 64 бит.
* Java openjdk version "11.0.6" 2020-01-14
* IntelliJ IDEA 2019.2.4 (Community Edition) version: 11.0.4+10-b304.77 amd64
