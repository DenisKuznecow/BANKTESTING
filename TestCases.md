#  [Test ID 1] 
## Test Case Name
* Добавление клиента с корректными входными данными
## Test Description
* (https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/openAccount)
## Pre-Conditions
* Валидные значения в полях "First Name", "Last Name" только буквенные кириллица и латиница вне зависимости от регистра
* Валидные значения в поле "Post Code" буквенные кириллица и латиница вне зависимости от регистра и цифровые 
## Test Steps
* Открыть страницу по ссылке через браузер Chrome   
* Ввод валидных значений в поле "First Name"
* Ввод валидных значений в поле "Last Name"
* Ввод валидных значений в поле "Post Code"
* Нажатие на кнопку Process
* Нажатие кнопки "Ок" на выводе алерта "Потверждение действия на www.globalsqa.com" 
## Expected Result
* Открыть вкладку "Customer"
* Убедиться что клиент добавлен в систему 


#  [Test ID 2] (https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/list)
## Test Case Name
* Сортировка клиентов по имени (First Name)
## Test Description
* (https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/list)
## Pre-Conditions
* Если добавлен клиент на латинице, изменение наименований идет согласно алфавитному порядку
* Если добавлен клиент на киррилице, изменение наименований идет согласно алфавитному порядку на кириллице с самого начала списка
## Test Steps
* Открыть страницу по ссылке через браузер Chrome
* Нажать на кнопку "First Name"
* Повторно нажать на кнопку "First Name"
## Expected Result 
* Изменение наименования списка клиентов согласно заданному Pre-Conditions


#  [Test ID 3] (https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/list)
## Test Case Name
* Поиск клиента по имени в поле "Search Customer"
## Test Description
* (https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/list)
## Pre-Conditions
* Добавить клиента в вкладке "Add Customer"
* Валидные значения в полях "First Name", "Last Name" только буквенные кириллица и латиница вне зависимости от регистра
* Валидные значения в поле "Post Code" буквенные кириллица и латиница вне зависимости от регистра и цифровые
## Test Steps
* Открыть страницу по ссылке через браузер Chrome
* Ввести нужное значение согласно внесенным данным в поле "Search Customer"
## Expected Result 
* Вывод имени клиентов по заданному значению по алфавиту


