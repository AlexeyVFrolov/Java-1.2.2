# **Отчёт о тестировании Precision**
## **Краткое описание**
08.03.2021 было проведено тестирование приложения для расчета итогового значения бонуса новым клиентам при пополнении. На тестирование затрачено времени: 0,1 часа. В результате выявлены следующие дефекты:
* [Потеря точности при вычислении totalBonus]()

## **Описание процесса тестирования**
В процессе тестирования использовались следующие артефакты: 
* [Файл с кодом Main.java]()

В качестве тестовых данных использовались данные:
* значение стандартного бонуса - 0.3 (три дсятых)
* значение специального бонуса - 0.6 (шесть десятых)

Тестирование производилось в следующем окружении:
* ОС Windows 10, 64-разрядная
* Java v. 11.0.10
* IntelliJ IDEA Community Edition 2020.3.2