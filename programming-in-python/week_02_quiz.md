# Тест по неделе 2

## Вопрос 1. 
Можно ли использовать изменяемые объекты в качестве значений по умолчанию в функциях?

* Нет, случится синтаксическая ошибка
* Да, но это может привести к неочевидным ошибкам


## Вопрос 2. 
Выберите верные утверждения про кортежи:

* проверка на вхождение элемента в кортеж происходит за константное время
* кортежи изменяемые
* проверка на вхождение элемента в кортеж происходит за линейное время
* кортежи неизменяемые
* кортежи могут содержать элементы различных типов


## Вопрос 3. 
Какой записи эквивалентно применение декоратора

```python
@login_required
def send_feedback(request)
```
?

* `login_required = send_feedback(login_required)`
* `send_feedback = login_required(send_feedback)`
* `def login_required(send_feedback)(request)`
* `def login_required(send_feedback)`

## Вопрос 4. 
Для чего используются декораторы?

* Для модификации поведения функций
* Для эффективного использования памяти при итерации
* Чтобы иметь возможность импортировать функцию в другой модуль

## Вопрос 5. 
Выберите верные утверждения про множества:

* проверка на вхождение элемента в множество происходит за линейное время
* множества изменяемые
* множества неизменяемые
* проверка на вхождение элемента в множество происходит за константное время

## Вопрос 6. 
Что происходит при итерации по генератору?

* Итерация происходит по списку значений, который вернул генератор при вызове
* Каждую итерацию вызывается функция `next`, и генератор исполняется с начала
* Каждую итерацию вызывается функция next, и исполнение генератора возобновляется с момента после `yield`