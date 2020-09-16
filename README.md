**Отчёт о тестировании Credit Card Number Validator.**

***Краткое описание***

16.09.2020 было проведено функциональное тестирование валидации номеров банковских карт. 

На тестирование затрачено: 0,1 часа

В результате тестирования выявлен следующий дефект:
[Невалидность номера кредитной карты American Express (AMEX)](https://github.com/elena-liashkova/Credit-Card-Number-Validator/issues/1)


**Описание процесса тестирования**

В процессе тестирования использовались следующие артефакты:
1) баг-репорт,
2) руководство по установке IntelliJ IDEA.

В качестве тестовых данных использовались [данные номеров карт с сервиса](https://cutt.ly/KfSsWfk):
 
VISA:
4929194301715232   **статус ОК**

MasterCard:
2720995276499486   **статус ОК**

American Express (AMEX):
346831267008994    **статус FAIL**

Visa Electron:
4026902998124571    **статус ОК**

Maestro:
6304606737097810    **статус ОК**

**Тестирование производилось в следующем окружении:**

 1. Java
•	Оpenjdk version "11.0.8" 2020-07-14
•	OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
•	OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
2.	Windows
•	Host Name: LENA-LAPTOP
•	Version 1909
•	OS Name: Microsoft Windows 10 Pro
•	OS Version: 10.0.18363 N/A Build 18363
3.	Browser Opera Version:70.0.3728.178

