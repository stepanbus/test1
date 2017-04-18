# Таблица
| HROUTEID | TO_QUEUE | JMS_TYPE | DESCR  | FAULT_QUEUE	| BANK |
| ------ | ----- | ------ | -----	| -----	| ---: |
| ADP. BROKER. REQ	| SRV. MSEXCH | EXCH_R_EMAILMESSAGE	| Почтовый шлюз MS Exchange. Запрос |	ADP.BROKER. RES.IN	| SKB, GEB  |
| SRV. MSEXCH. OUT	| ADP. BROKER. RES.IN	| EXCH_A_EMAILMESSAGE |	Почтовый шлюз MS Exchange. Ответ  |	ADP.BROKER. RES.IN	| SKB, GEB  |
