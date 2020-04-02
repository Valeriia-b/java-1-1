# Отчет о тестировании KeyValidator
## Краткое описание
02.04.2020 проведено функциональное тестирование приложения KeyValidator.\
На тестирование затрачен 1 час.\
В результате тестирование выявлены следующие дефекты:
* [часть валидных ключей не прошла проверку на подлинность](https://github.com/Valeriia-b/java-1-1/issues/1)
* [часть невалидных ключей прошла проверку на подлинность](https://github.com/Valeriia-b/java-1-1/issues/2)
## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* Тест-план, описанный в [Легенде](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)
* баг-репорты
* отчет о тестировании

В качесте тестовых данных использовались данные, указанные в [Руководстве использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md).

Для каждого из указанных валидных ключей статус проверки должен быть OK.

Для каждого из указанный невалиных ключей статут проверки должен быть FAIL.

Тестирование проводилось в следующем окружении:
* ОС: Winows 7 x64
* Java version: openjdk 11.0.6 2020-01-14\
  OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)\
  OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)\
* git version 2.25.1.windows.1


