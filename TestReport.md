# Отчёт о тестировании приложения "Money Transfer"

## Краткое описание
Для тестирования были взяты данные клиента Альфа-банка, при переводе которого произошла ошибка.
для проверки были использованы переменные типа int.
В ходе тестирования было выявлено несоответствие ожидаемой суммы баланса и фактической.

## Краткое описание проведённой работы.
Проводилось позитивное функциональное тестирование
* int balance = 2_000_000_000;
* int transfer_amount = 500_000_000;
* int total = balance + transfer_amount;
итоговое значение -1794967296
ожидаемое значение: 2500000000

## Результаты
1. 0% успешных тестов, 100% неуспешных тестов.<br>
2.[Сумма баланса после перевода имеет отрицательное значение][1]

## Общие рекомендации

Требуется проверить правильность использования типа переменных для расчёта данных значений.

[1]: https://github.com/mkorolkova311/MoneyTransfer/issues/1
