# Тест-кейс №1
## Идентификатор тест-кейса: TC001
## Название тест-кейса: Доступность колонки «Наименование товара» для заполнения пользователем
## Предусловия: Пользователь залогинен в системе. Пример пользователя user@example.com и пароль password123
## Шаги выполнения: 
1.	В верхнем меню нажать на кнопку «Накладная»
2.	Ввести значение в поле «Наименование товара»
## Ожидаемый результат: Колонка «Наименование товара» доступна для заполнения пользователем
## Фактический результат: (заполняется после выполнения теста)
## Окружение: Windows 10, Версия 22H2

# Тест-кейс №2
## Идентификатор тест-кейса: TC002
## Название тест-кейса: Недоступность строки «Итого» для заполнения пользователем
## Предусловия: Пользователь залогинен в системе. Пример пользователя user@example.com и пароль password123
## Шаги выполнения: 
1.	В верхнем меню нажать на кнопку «Накладная»
2.	Ввести значение в поле «Итого»
## Ожидаемый результат: Строка «Итого» недоступна для заполнения пользователем
## Фактический результат: (заполняется после выполнения теста)
## Окружение: Windows 10, Версия 22H2

# Тест-кейс №3
## Идентификатор тест-кейса: TC003
## Название тест-кейса: Автоматические заполнение колонки «Сумма» в соответствии с формулой (Кол-во)*(Цена) 
## Предусловия: Пользователь залогинен в системе. Пример пользователя user@example.com и пароль password123
## Шаги выполнения: 
1.	В верхнем меню нажать на кнопку «Накладная»
2.	Ввести значение в поле «Наименование товара»
3.	Ввести значение в поле «Кол-во», соответствующее количеству введённого товара
4.	Ввести значение в поле «Цена», соответствующее цене одной единицы введённого товара
5.	Нажать Enter
## Ожидаемый результат: Колонка «Сумма» автоматически заполняется в соответствии с формулой (Кол-во)*(Цена) 
## Фактический результат: (заполняется после выполнения теста)
## Окружение: Windows 10, Версия 22H2

# Тест-кейс №4
## Идентификатор тест-кейса: TC004
## Название тест-кейса: Автоматический счёт и вывод суммы всех значений для колонок «Кол-во» и «Сумма» в строке «Итого»
## Предусловия: Пользователь залогинен в системе. Пример пользователя user@example.com и пароль password123
## Шаги выполнения: 
1.	В верхнем меню нажать на кнопку «Накладная»
2.	Ввести значение в поле «Наименование товара» в первой строке
3.	Ввести значение в поле «Кол-во», соответствующее количеству введённого товара в первой строке
4.	Ввести значение в поле «Цена», соответствующее цене одной единицы введённого товара в первой строке
5.	Нажать Enter
6.	Ввести значение в поле «Наименование товара» во второй строке
7.	Ввести значение в поле «Кол-во», соответствующее количеству введённого товара во второй строке
8.	Ввести значение в поле «Цена», соответствующее цене одной единицы введённого товара во второй строке
9.	Нажать Enter
## Ожидаемый результат: В строке «Итого» автоматически считаются и выводятся суммы всех значений для колонок «Кол-во» и «Сумма»
## Фактический результат: (заполняется после выполнения теста)
## Окружение: Windows 10, Версия 22H2


