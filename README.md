# Финальный проект спринта 6 курса Яндекс Практикум "Автоматизатор тестирования на Java"

### Технологии проекта:

Java 11, JUnit4, Maven, Jacoco

### Как запускать:

`mvn clean test`
___________________________________________________________________________________
### Описание проекта:

Тебя пригласили помочь зоологам: они исследуют семейство кошачьих. Чтобы записывать наблюдения, учёные используют специальную программу. Тебе предстоит протестировать часть программы. 

## Техническое задание

### Обязательное задание

- Привяжи GitHub к тренажёру. Как только ты это сделаешь, в списке репозиториев автоматически появится qa_java. Там будет заготовка проекта, в которой нужно дописать код.
- Собери Maven-проект: подключи Jacoco, Mockito и JUnit.
- Класс Lion не должен зависеть от класса Feline. Используй принцип инъекции зависимостей.
- Напиши моки с помощью Mockito. Какие именно понадобятся — определи самостоятельно.
- Напиши тесты на классы Feline, Cat и Lion.
- Подумай, где можно применить параметризацию. Реализуй параметризованные тесты.
- Оцени покрытие с помощью Jacoco: оно должно быть не менее 100% для классов Feline, Cat и Lion.

### Дополнительное задание

1. Создай класс льва Алекса из мультфильма «Мадагаскар». Он будет наследником обычного льва.
Помимо обычных методов у него есть свои:
- getFriends() возвращает список имён его друзей — зебры Марти, бегемотихи Глории и жирафа Мелман;
- getPlaceOfLiving() возвращает место, где он живёт — Нью-Йоркский зоопарк.
Также нужно переопределить метод getKittens(), потому что у Алекса нет львят. А ещё — написать свой конструктор, так как в классе Lion нет дефолтного конструктора. Алекс самец, поэтому в конструктор класса Lion всегда будет передаваться одно и то же значение.
2. Покрой тестами созданный класс.
