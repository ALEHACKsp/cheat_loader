Привет пастеры. Мне немного надоело что люди используют мою объективно не очень разработку под названием GreenLoader.
И специально для вас я решил выпустить это. Данная разработка подойдет для тех кто слишком глуп или напротив слишком умен, чтобы что-то делать самому.

Функции: Manualmap inject, authorization, menu, support x32 / x64, store & restore data

![image](https://user-images.githubusercontent.com/45714660/141278916-49701598-ecb5-485a-90e5-7f55595eaad6.png)
![image](https://user-images.githubusercontent.com/45714660/141278928-dbc9596b-1811-47de-8ac7-ee8cc9ece64a.png)
![image](https://user-images.githubusercontent.com/45714660/141278935-14fd981d-019b-4589-95c2-13512e05fade.png)

Теперь все гораздо проще чем раньше.
Чтобы завести все под себя, открываем сурс, жмем CTRL+F, ставим все решение и ищем строку CHANGE THIS. Пример:
![image](https://user-images.githubusercontent.com/45714660/141278955-efd7d76c-2292-4fb8-98a0-13b932f3dc42.png)

Мануалмап скорее всего инжектит в кс. Авторизация написана на кастомной либе auther.quarc.me. В нее я добавил ксор и переписал названия функций, чтобы рофло-реверсеры словили мем на локальных импортах. Если будете пересаживать либу на x32, то хедер тоже меняйте.
Защиты нет, потому что спастите ее сами. Получение статуса чита реализовано через нищерский сокет.
Если вы пастер то можете с помощью него также сделать проверку на версию. Функционал более чем достаточный.
Ключ через store data сохраняется на диск C в папку PastawareGaySex.

МАНУАЛМАП ПОДДЕРЖИВАЕТ ВМП И ПРОЧИЙ КАЛ!

Спащено: мануалмап(небольшие изменения), функция что гетает строку через сокет.
