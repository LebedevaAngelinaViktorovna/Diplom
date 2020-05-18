# Diplom
1) Базовое ООП приложение состоит из следующих файлов: client.py и server.py - программы клиент-сервер, student.py, discipline.py, administrator.py - файлы с описанием классов Student, Discipline и Administrator, list.txt - список студентов и администраторов, disciplines.txt - список предметов, остальные текстовые файлы - ведомости по соответствующим предметам.

Для запуска базового приложения в терминале сначала вводится команда sudo python3 server.py (сначала запускается программа-сервер, для Ubuntu), затем в другом окне терминала запускается клиент: python3 client.py. Первым делом программа-клиент потребует ввод логина и пароля. Их можно выбрать из файла list.txt. Предполагается, что логины и пароли заранее известны пользователям. Итак, в систему можно зайти в качестве студента или администратора. У администратора больше прав, он может изменить любое из полей студента (фамилия, курс, группа и тд), зарегистрировать нового, удалить из системы студента, посмотреть зачетку любого студента, узнать рейтинг и изменить пароль. Студент же может только узнать свои оценки, рейтинг и поменять свой пароль.
Видео работы приложения доступно по ссылке https://drive.google.com/file/d/1mt90sfslXOsx7ifn1WZpTCK1pZPdlK6u/view?usp=sharing.
