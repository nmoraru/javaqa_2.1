# Отчёт о тестировании KeyValidator

## Краткое описание

25.03.2020 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [000001 Ключ из всех нулей не валиден](https://github.com/nmoraru/javaqa_1.1/issues/1)
* [000002 Некорректный список валидных ключей](https://github.com/nmoraru/javaqa_1.1/issues/2)
* [000003 Некорректные список невалидных ключей](https://github.com/nmoraru/javaqa_1.1/issues/3) 

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство использования KeyValidator](https://github.com/nmoraru/javaqa_1.1/blob/master/user-manual.md)

В качестве тестовых данных использовались данные [Руководство использования KeyValidator](https://github.com/nmoraru/javaqa_1.1/blob/master/user-manual.md):
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 : OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 : OK
* b295bc63-9f03-3b4b-af80-969b39f8c262 : OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317 : OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 : OK
* 18252235-78e0-44a5-8720-556f0c7da17a : FAIL
* e66075b6-ddad-445e-baf6-161b3289522b : FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca : FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42 : FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 : FAIL
* 00000000-0000-0000-0000-000000000000 : OK
* 00000000-0000-0000-0000-000000000001 : FAIL

Тестирование производилось в следующем окружении:
* Windows 10 Pro 64 бит.
* Java openjdk version "11.0.6" 2020-01-14
* git version 2.26.0.windows.1
