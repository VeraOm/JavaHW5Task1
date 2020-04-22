#  Отчет о тестировании Задачи №1 - Дописываем тесты
20.04.2020 - 20.04.2020 было выполнено задание "Дописываем тесты".

На тестирование 2 часа

В результате тестирования выявлены следующие дефекты:
* дефекты не выявлены

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «2.3. Система сборки Maven, управление зависимостями, автотесты на JUnit5»](https://github.com/netology-code/javaqa-homeworks/tree/master/maven-junit/README.md)


В качестве источника тестовых данных использовались данные составленные согласно требованиям Задачи №1 артефакта "Домашнее задание к занятию «2.3. Система сборки Maven, управление зависимостями, автотесты на JUnit5»":
* Метод shouldCalculateForRegisteredAndUnderLimit, переменная expected - 30, переменная amount - 1000_60
* Метод shouldCalculateForRegisteredAndUnderLimit, переменная expected - 500, переменная amount - 1000_60
* Метод shouldCalculateForRegisteredAndUnderLimit, переменная expected - 499, переменная amount - 16_666_66
* Метод shouldCalculateForUnRegisteredAndUnderLimit, переменная expected - 30, переменная amount - 1000_60
* Метод shouldCalculateForUnRegisteredAndUnderLimit, переменная expected - 10, переменная amount - 1000_60
* Метод shouldCalculateForRegisteredAndOverLimit, переменная expected - 500, переменная amount - 1_000_000_60
* Метод shouldCalculateForRegisteredAndOverLimit, переменная expected - 30, переменная amount - 1_000_000_60
* Метод shouldCalculateForRegisteredAndOverLimit, переменная expected - 500, переменная amount - 16_666_67
* Метод shouldCalculateForUnRegisteredAndOverLimit, переменная expected - 30, переменная amount - 1_000_000_60
* Метод shouldCalculateForUnRegisteredAndOverLimit, переменная expected - 500, переменная amount - 1_000_000_60

Тестирование производилось в следующем окружении:
*  ОС: Windows x64 Home
* Java: openjdk version "11.0.6" 2020-01-14
   OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
   OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
* Файл исходного текста тестируемого класса BonusServiceTest: https://github.com/VeraOm/JavaHW5Task1/blob/master/src/test/java/BonusServiceTest.java
* Файл исходного текста класса BonusService: https://github.com/VeraOm/JavaHW5Task1/blob/master/src/main/java/BonusService.java
* Файл настройки проекта Maven: https://github.com/VeraOm/JavaHW5Task1/blob/master/pom.xml
