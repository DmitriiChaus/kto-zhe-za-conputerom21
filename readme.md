# Telegram-bot - "А кто же закомпьютером?"
 
## Библиотеки
numpy
face_recognition
cv2
os
datetime
telebot 
csv


## Структура проекта
	- tdes.py -- главный файл проекта
	- tg.py -- файл проекта с реализацией телеграмм-бота
	- imena.csv -- файл, в который записываются имена пользователей и время
	- faces -- папка, содержащая картинки пользователей(с которыми сравниваются лица при помощи веб-камеры)

	

## Работа с приложением
Запустить два файла tdes.py и tg.py.
Открыть телеграмм и ввести в поисковую строку "@face_checker_bot".
Написать боту "/start".
Бот напишет, что делать следом.
Необходимо выполнять команды бота.
В итоге, телеграмм-бот напишет имя пользователя, сидящего за компьютером.  

## Особенности проекта
проверка лиц пользователей компьютера с помощью веб-камеры. 
Используя метод compare_faces из библиотеки face-recognition, сравниваются лица из папки faces с лицом пользователя, которое появится на веб-камере. 
Имена и время записываются в файл формата csv.
Созданный телеграмм-бот прост в повседневной жизни, им может пользоваться даже необученный человек(ребенок, пожилой человек).
На сегодня не так развиты телеграмм-боты, проверяющие безопасность в доме при помощи камер и передающих информацию в телеграмм. 
Проект может получить продолжение. Например, внедрение телеграмм-бота в систему "Умного дома" или использование в системе "Face ID" на входе в какое-либо заведение.
