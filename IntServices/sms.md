«Шлюз СМС сервера»
===========================
Версия 1.0.0
------------





 
## Оглавление

1.Термины	
2.Краткое описание
3.Описание	
    3.1.Общая схема взаимодействия


 
## 1.	Термины
Шлюз смс сервера это шлюз для смс сервера, и точка

 
## 2.	Краткое описание
Для того шлюз и предназначен, чтобы слать смски

 
## 3.	Описание 
## 3.1.	Общая схема взаимодействия
1.	Полученное от прикладной системы сообщение оправляется получателю через Exchange, при этом прикладная система информируется о стадиях обработки сообщения шлюзом;
2.	Обработчик шлюза, при необходимости, отслеживает состояния отправленных сообщений и информирует прикладную систему о доставке/недоставке, прочтении или времени истечения таймаутов отслеживания  этих состояний.  Производится очистка неактуальной информации в почтовом ящике Exchange.
Результатом работы является отправка почтового сообщения и получение прикладной системой информации о жизненном цикле сообщения (обработке, формировании, отправке, доставке, прочтении), как показано на Рисунке 2.
Маршрут следования сообщений представлен на Рисунке 1.
![Медведь](/IntServices/sms/Koala.jpg "Медведь")
