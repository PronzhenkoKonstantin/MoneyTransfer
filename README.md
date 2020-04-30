# Отчёт о тестировании Money Transfer
## Необходимо проверить функциональность перевода средств Money Transfer.
Дата начала-27.04.2020 16-00  
Дата окончания 27.04.2020 17-00 

Было проведено модульное тестирование, возможность корректного суммирования перевода и текущего баланса средств в приложении Money Transfer.

**На тестирование затрачено:** 1 час

В результате тестирования выявлены следующие дефекты:

1.https://github.com/PronzhenkoKonstantin/MoneyTransfer/issues/1#issue-609806375

**Описание тестирования:**

Написали базовое приложение для суммирования баланса денежных средств с суммой переведенных денежных средств, используя переменные:
int balance = 2_000_000_000;
int transfer = 500_000_000;
Запустили данную программу
Полученный результат с отрицательным резуьтатом: "C:\Program Files\AdoptOpenJDK\jdk-11.0.7.10-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1\lib\idea_rt.jar=49215:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\ПК\IdeaProjects\untitled3\out\production\untitled3 Main
-1794967296

**В качестве тестовых данных использовались данные:**

https://github.com/netology-code/javaqa-homeworks/tree/master/programming

**Тестирование производилось в следующем окружении:**
Windows 7, 64-bit
Java 8
IntelliJ IDEA Community Edition 2020.1 x64