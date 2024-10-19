В проекте были использован сервер и клиент для отображения информации.
На сервере была создана БД Books для хранения информации о списке книг, в клиенте же они просто выводятся с возможностью их редактировния/удаления/добавления.
Были произведены запросы (GET.POST,PUT,DELETE) в приложениии Postman с помощью файла serializers.py.

Сервер был разработан на django-restframework
Интерфейс сервера
![image](https://github.com/user-attachments/assets/bdcbd115-cef7-4305-8854-7f5037c0861a)


Модель Books:

![image](https://github.com/user-attachments/assets/ee9a4db2-d7bd-4682-931c-13fbcd7c8b67)

Были созданы поля: id, автор, название и прочитано/не прочитано

Serializers.py:

![image](https://github.com/user-attachments/assets/fca4258f-b227-40a5-a83d-297b1cd9beb0)

GET

![image](https://github.com/user-attachments/assets/fd44f59a-f233-45ef-b853-ea89785b8a91)

POST

![image](https://github.com/user-attachments/assets/c07aee98-0600-45c3-a0d5-8293fe7206d9)

PUT

![image](https://github.com/user-attachments/assets/648619c5-73ef-46ae-ba92-3bf52904d3e8)

DELETE

![image](https://github.com/user-attachments/assets/236a9238-8b01-499a-8ee3-e24d4370d005)

##Клиент

Клиент разработан на основе vue.
Интерфейс клиента
![image](https://github.com/user-attachments/assets/f8fc262f-5f46-44f2-a95b-92598c776c19)

Добавление книги
![image](https://github.com/user-attachments/assets/6717e584-5a0c-40a4-962f-5c224779c9e8)

Редактирование книги
![image](https://github.com/user-attachments/assets/5659bc91-a9c7-401d-8f4c-25d7d64a39d7)

Удаление книги
![image](https://github.com/user-attachments/assets/d9527782-dee3-4c89-b00f-e4a0b3ddc7a8)




