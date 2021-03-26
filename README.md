## Отчет о тестировании

Jacoco воспроизводит информацию о проведенном тестировании в следующем виде:

![StatisticsService - Google Chrome 2021-03-26 23 04](https://user-images.githubusercontent.com/11545844/112674371-a979e800-8e87-11eb-92dd-96bc884da72b.png)



Как правило, в первую очередь оцениваются следующие показатели:

1. `INSTRUCTION`

1. `LINE`

1. `BRANCH`

INSTRUCTION показывает процент покрытия тестами операторов циклов, условных операторы и т.п., имеющихся в коде.

LINE показывает процент покрытия тестами строк кода.

BRANCH показывает процент покрытия тестами всех "ответвлений" алгоритма.

Таким образом, все эти показатели неразрывно взаимосвязаны между собой. Ведь алгоритм невозможен без **операторов**, которые передают значения в новую **строку**, которая соответствует новой **ветке**.

#### Соответственно, достичь 100% невозможно только для одного счетчика.