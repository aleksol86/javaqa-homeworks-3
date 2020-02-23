# Отчёт о тестировании 
## Краткое описание
22.02.2020 было проведено тестирование Money Transfer

На тестирование затрачено: 1 час

В результате тестирования не выявлено дефектов

## Описание процесса тестирования
 В процессе тестирования использовались следующие артефакты:
* [Входные данные в Задаче №1](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#задача-1---money-transfer)

В качестве тестовых данных использовался код программы: 
```
 public class Main1 {
    public static void main(String[] args) {
        int balance = 2_000_000_000;
        int transfer = 500_000_000;
        int total = balance - transfer;
        System.out.println(total);
    }
}
```

* Тестирование работы кода программы и запуск с входными данными:

  * Запустить установленную программу IntelliJ IDEA
  * В Project нажать Alt+Insert и выбрать Java Class
  * В поле окна New Java Class ввести Main1
  * Скопировать код из тестовых данных
  * Нажать Ctrl+Shift+F10
  * Ожидаемый результат: значение 1500000000


Тестирование производилось в следующем окружении:
* Windows 7 SP1 x64
* Java 11
* Git c оболочкой Bash 
* IntelliJ IDEA  2019.3.3