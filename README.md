# Отчёт о тестировании Precision

Протестировать код новой функции приложения по добавлению бонусов клиентам 
09.04.2021 было проведено полуавтоматизированное тестирование базового приложения Precision

На тестирование затрачено: 0:10 

### В результате тестирования выявлены следующие дефекты:
**[Расчет бонусов неверна
](https://github.com/avbochkareva/java1.3/issues/2)**

### Процесс тестирования

В процессе тестирования использовались следующие артефакты:
* Cоздать новый проект по тестированию на IntelliJ IDEA 2020.3.3 
* Написать базовое приложение, используя [данные](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
```
public class Main {
public static void main(String[] args) {
double regularBonus = 0.3;
double specialBonus = 0.6;
double totalBonus = regularBonus + specialBonus;
System.out.println(totalBonus);
}
}
```
* Запустить проверку

### Тестирование производилось в следующем окружении:
* Windows 10, x64
* версия Java - 11.0.10
* IntelliJ IDEA 2020.3.3 
