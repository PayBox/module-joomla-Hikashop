# Hikashop 2.3
#### Тестировалось на Joomla версия 3.3.3 и Hikashop 2.3.3.
1. Регистрируемся на <a href="https://paybox.money" target="_blank">paybox.money</a>
2. Копируем папку plugins в корень сайта
3. Исполняем в базе данных запрос из файла mysql.install.sql, меняя префикс #__ на префикс таблиц в вашей базе данных
4. Выбираем раздел способы оплаты в панели управления hikashop
5. Добавляем новый метод оплаты Paybox
6. Настраиваем способ оплаты* (редактировать):

\* Чтобы не принимать оплату по конкретной транзакции – поменяйте статус заказа в отличный от статуса, который вы поставили, как ожидающий оплаты. SUCCESS_URL и FAILURE_URL – ссылки, куда вернется пользователь после оплаты. PAYMENT_SYSTEM заполняется, если вы хотите, чтобы выбор платежной системы происходил на стороне магазина. Для этого нужно добавить столько платежных методов, сколько у Вас платежных систем подключено в Paybox.
