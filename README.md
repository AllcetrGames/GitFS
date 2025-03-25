# JustFS #1.0
Репозиторий для модуля JustFS (JustFileSharing)

# СОЗДАНИЕ ФАЙЛА

Сначала создайте текстовый файл в репозитории c любым именнем. Далее выберите тип файла: **Картинка (image) или Текст (text)** и напишите в текстовый файл
```type=Тип```
Потом напишите само содержимое запроса. 
# ЕСЛИ СОДЕРЖИМОЕ: ТЕКСТ

Напишите **content=** и сам текст.
```content=Текст```

Тестовый файл с **типом текст** с текстом **Hello world**:
```type=text
content=Hello world```

# ЕСЛИ СОДЕРЖИМОЕ: КАРТИНКА

Перейдите на https://imgur.com/upload и загрузите свою картинку. После скопируйте ссылку и напишите

```content=Ссылка```

![2025-03-25_22-15-37](https://github.com/user-attachments/assets/3d2e2be9-9d93-49e0-bbd6-9aef7d7ee2eb)

Тестовый файл с **типом image** с ссылкой на картинку **https://imgur.com/90icNxE**:

```type=image
content=https://imgur.com/90icNxE```

# ПЕРЕНОС НА JUSTMC

Сначала загрузите модуль JustFS.
```/module load AllcetrGD/justfilesharing```
Затем перейдите в репозиторий и откройте свой файл. Потом нажмите **Raw** и скопируйте ссылку нового окна.

