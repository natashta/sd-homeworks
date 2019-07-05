# Домашнее задание к лекции «Знакомство с JavaScript»

![results](../assets/results.png)

Мы будем делать игру в кости — Крэпс. Немного упростим правила, но суть останется прежней. Бросается два кубика — в зависимости от суммы результатов, игрок или выиграл или проиграл или должен перекинуть кости.

Вертска (разметка и визуальное представление) игры уже готово, а в прошлом домашнем задании вы реализовали логику броска. Теперь необходимо добавить выведение результата на экране.

В проекте существует подпрограмма (небольшая часть программы) отвественная за выведение результата на экран. Сейчас она всегда после броска выводит 1. Ваша задача — выводить результата настоящего броска.

**Алгоритм работы:**
+ Откройте в папке `game` файл `playGame.js`.
+ Внутри подпрограммы `playGame` замените присваивание единиц в `firstResult` и `secondResult`, вызовом своей подпрограммы — `rollDiece`