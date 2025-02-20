﻿# **Лабораторная работа №8. Паттерн «Состояние»**

- [**Лабораторная работа №8. Паттерн «Состояние»**](#лабораторная-работа-8-паттерн-состояние)
  - [Критерии оценивания лабораторной работы](#критерии-оценивания-лабораторной-работы)
  - [Обязательные задания](#обязательные-задания)
    - [Задание 1 – Покрыть тестами функционал класса GumballMachine – 100 баллов](#задание-1--покрыть-тестами-функционал-класса-gumballmachine--100-баллов)
    - [Задание 2 – MultiGumballMachine – 70 баллов](#задание-2--multigumballmachine--70-баллов)
      - [Бонус +50 баллов за покрытие тестами](#бонус-50-баллов-за-покрытие-тестами)
    - [Задание 3 – Обработать ситуацию с заполнением автомата жвачкой во всех состояниях – 70 баллов](#задание-3--обработать-ситуацию-с-заполнением-автомата-жвачкой-во-всех-состояниях--70-баллов)
      - [Бонус +50 баллов за покрытие тестами](#бонус-50-баллов-за-покрытие-тестами-1)
    - [*Задание 4 – Добавить меню к программе – 50 баллов*](#задание-4--добавить-меню-к-программе--50-баллов)

## Критерии оценивания лабораторной работы

При сдаче лабораторной работы студент должен уметь ответить на вопросы преподавателя насчёт используемых паттернов проектирования,
уметь изобразить схему паттерна на диаграмме классов, а также продемонстрировать диаграмму классов своего приложения.

- На оценку «удовлетворительно» необходимо набрать 70 баллов.
- На оценку «хорошо» необходимо набрать 200 баллов.
- На оценку «отлично» необходимо набрать 350 баллов.

## Обязательные задания

### Задание 1 – Покрыть тестами функционал класса GumballMachine – 100 баллов

Покрыть реализацию, использующую паттерн состояние, юнит-тестами. Тестами должны быть покрыты классы состояний и сама машина.

### Задание 2 – MultiGumballMachine – 70 баллов

Доработать GumballMachine, чтобы автомат мог принимать до пяти монеток. Каждый поворот рычага может выдавать по одному шарику.
При этом можно опускать дополнительные монетки, не дожидаясь выдачи всех шариков.
Одно нажатие кнопки возврата монетки должно возвращать все монетки.

Если монеток больше, чем шариков, то после выдачи последнего шарика пользователь должен иметь возможность монетки вернуть.

Данный функционал сделать в двух реализациях – наивной и использующей паттерн «Состояние».
Сравнить характер проделанных изменений. Сделать выводы.

#### Бонус +50 баллов за покрытие тестами

Бонус начисляется за покрытие обеих реализаций тестами.

### Задание 3 – Обработать ситуацию с заполнением автомата жвачкой во всех состояниях – 70 баллов

Наполнение автомата жвачкой должно быть возможным в любом состоянии автомата кроме состояния выдачи жвачки.
При этом вставленные монетки/монетка не должны пропасть.

#### Бонус +50 баллов за покрытие тестами

### *Задание 4 – Добавить меню к программе – 50 баллов*

Добавить к приложению интерактивность, используя класс меню из лабораторной работы по паттерну «Команда».
