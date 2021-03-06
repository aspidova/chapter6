# Глава 6. Обучение робота слушать

Научить робота воспринимать устные инструкции - это целая отдельная дисциплина. Машина должна не просто распознавать отдельные слова или какие-то банальные фразы. Мы хотим, чтобы он мог реагировать на достаточно большое разнообразие фраз. Можно сказать: "Подбери игрушки." или "Пожалуйста, подбери все игрушки." или "Убери этот беспорядок!", любая из этих команд должна быть инструктирующей начать уборку. 

В этой главе используются различные техники и процессы. Мы будем создавать вербального помощника с открытым исходным кодом по имени Mycroft. Это основанный на искусственном интеллекте алгоритм распознавания речи и обработки естественного языка, который может быть нами запрограммирован и расширен. Мы добавим в него некоторые дополнительные возможности - будет использоваться техника, которую я называю “заполнение пробелов, методом обработки команд”, чтобы извлечь смысл голосовых инструкций пользователя и, следуя им, робот делал то, что вы хотите, даже если это не совсем то, что вы сказали. Мы завершим эту главу, научив робота рассказывать шутки "тук-тук" и отвечать на них.

#### **В этой главе будут рассмотрены следующие темы:**

*   Обработка естественного языка
* Выводы из контекста
* Понимание намерений
* Распознавание речи
* Текст в речь
* Диалоговое окно вызова и ответа для шуток тук-тук

