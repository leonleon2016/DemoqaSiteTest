# DemoqaSiteTest
Выполненное тестовое задание для компании ITFB Group с использованием среды тестирования TestNG, паттерна PageObject и фреймворка Allure для автоматического составления отчетов. Тест проверяет функционал сайта https://demoqa.com. В частности проверяется:

1)Функционал всплывающих окон: https://demoqa.com/alerts

2)Функционал кнопок на странице: https://demoqa.com/buttons

3)Заполнение формы и проверка корректности вводимых данных на странице: https://demoqa.com/text-box

4)Создание окон и закладок на странице: https://demoqa.com/browser-windows


В функционале всплывающих окон проверяется:  

   1)Простое всплывающее окно - в тесте производится клик на первую кнопку "Click me", после чего появляется всплывающее окно, дальше производится клик на кнопку "OK" на всплывающем окне.

   2)Всплывающее окно с задержкой - производится клик на вторую кнопку "Click me", после чего с задержкой в пять секунд появляется всплывающее окно, после этого надо кликнуть на кнопку "OK" на всплывающем окне.

   3)Всплывающее окно с подтверждением - производится клик на третью кнопку "Click me", появляется окно, надо нажать на кнопку подтверждения "OK" и проверить что зеленая надпись "You selected Ok" появилась рядом с кнопкой.

   4)Всплывающее окно с полем ввода - производится клик на четвертую кнопку "Click me", вводится имя в поле, дальше производится клик на кнопку "OK" и проверятся появившееся сообщение рядом с кнопкой. Сообщение должно содержать имя, введённое в поле всплывающего окна.

В функционале кнопок проверяется:

   1)Кнопка "Double Click me" - нужно произвести двойной клик и проверить, что появилась запись "You have done a double click"

   2)Кнопка "Right Click me" - нужно произвести клик правой кнопкой мыши и проверить, что появилась запись "You have done a right click"

   3)Кнопка "Click me" - нужно произвести клик на кнопку и проверить, что появилась запись "You have done a dynamic click". Кнопка с динамическим id.

На странице формы заполняются поля: Full Name, Email, Current Address, Permanent Address. После клика на кнопку "Submit" ниже появляются введенные данные. Нужно проверить, что отображаются именно те данные, которые были введены в поля сверху. 

На странице создания окон и закладок проверяется:

   1)Создание закладки по клику на кнопку "New Tab" - по клику создается новая закладка, после переключения на новую закладку срабатывает код по закрытию закладки.

   2)То же самое что в первом пункте, но с тем лишь исключением, что создается окно вместо закладки по клику на кнопку "New Window".

После успешного прохождения автотестов автоматически генерируется отчет с помощью фреймворка Allure.
