# Домашнее задание к занятию 2.4. «Инструменты тестирования. Клиент-Сервер»

## Задание 1

Руководитель планирует запустить проект в закрытое бета-тестирование. В закрытом тестировании будут участвовать члены семьи руководителя, включая бабушку. Поэтому нам нужно проверить, выдержит ли наша анкета одновременную работу 15 человек, или кому-то придётся пить кофе, пока остальные тестируют. 

Ссылка на анкету - http://zayavka-na-kartu-3.sdew.ru/

Мы знаем, что есть специальный инструмент, при помощи которого мы можем проверить нагрузку – [JMeter](https://jmeter.apache.org/)

Задача:
* При помощи JMeter создайте один профиль нагрузки (на выбор, объяснить выбор) из рассмотренных на лекции.

* Запустите одновременно 15 потоков.

* Предоставьте отчёт о результатах запуска. 

Результат задания: ссылка на файл с 3 скриншотами, которые должны отображать: 1. Request файл; 2. Thread файл; 3. Listener файл


## Задание 2 

В ходе закрытого бета-тестирования бабушка руководителя проекта случайно нажала не туда и отправила что-то непонятное на сервер. Сервер от неожиданности лег. Шаги для воспроизведения бабушка забыла, но помнит, что где-то меняла запрос. Нужно попробовать повторить действия бабушки. 

Бабушка своих действий не помнит. Но зато у нас есть инструменты, позволяющие перехватывать трафик и менять его. Все они были рассмотрены на лекции.

Задача:
Используя инструмент Postman, изменить запрос и послать на сервер не то, что он ожидает. Не обязательно ломать систему, главное – попробовать изменить запрос и посмотреть на результат.

Результат задания: файл с отчётом о проделанной работе + скриншот(ы).

Подсказка: 
Для отправки запроса можно использовать body(raw), где указать, что отправлять в формате json.
К примеру, вот так: 

```
{
"birthday": "13.06.1999",
"name": "тест",
"passport": "4444 № 44444444",
"patronymic": "тест",
"phone": "+7 (999)-999-99-99",
"surname": "тест"
}
```

## Задание 3

Ответьте, пожалуйста, правильно на следующие вопросы, выбрав только один верный вариант:

### 1. Что означает термин «логическая бомба»?

1. программа, выполняющая вредоносный код при определенных условиях 
2. вредоносный вирус
3. вредоносный интернет-червь
4. вредоносная программа, скрывающаяся в безвредном приложении


### 2. Как называют программу или код для обхода стандартного механизма аутентификации?

1. бэкдор
2. троян
3. вирус
4. программа-вымогатель 
5. интернет-червь

### 3. Пользователь видит на экране сообщение о том, что доступ к данным закрыт и будет восстановлен только после уплаты некоторой денежной суммы. К какой категории относится вредоносное ПО, выводящее такие сообщения?

1. логическая бомба
2. вирус
3. интернет-червь
4. программа-вымогатель 

### 4. Как называют сценарий, при котором злоумышленник отправляет мошенническое электронное сообщение, выдавая его за сообщение из надежного источника?

1. фишинг
2. бэкдор
3. троян
4. вишинг

### 5. Что именно модифицируют руткиты?

1. хранителей экрана
2. блокнот
3. Microsoft Word
4. программы
5. операционную систему

### 6. Чем вирусы отличаются от интернет-червей?

1. Вирусы, в отличие от интернет-червей, скрываются в безвредных приложениях.
2. Вирусы могут распространять копии самих себя без участия пользователя. Интернет-черви не имеют такой способности.
3. Интернет-червям необходим файл-носитель. Вирусы не нуждаются в таком файле.
4. Интернет-черви могут распространять копии самих себя без участия пользователя. Вирусы не имеют такой способности.

Результат задания: 6 ответов, с номером вопроса, номером ответа и его определением.

## Как сдать домашнее задание
Результат выполнения домашнего задания в виде текста или ссылок отправить на проверку из личного кабинета.
Файлы или архивы через личный кабинет отправлять не нужно!

Все задания обязательны к выполнению для получения зачета, кроме дополнительных задач, помеченных `*`. 
Любые вопросы по решению задач задавайте в чате Slack.

