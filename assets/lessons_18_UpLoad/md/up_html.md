```php
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Загрузить файл</title>
</head>

<body>
    <a href="list.php" style="text-align: center">Список файлов</a><br>
    <form action="up.php" method="post" enctype="multipart/form-data">
        <input type="hidden" name="MAX_FILE_SIZE" value="1000000">
        <input type="file" name="userfile" size="20"><br><br>
        <input type="submit" value="Отправить">
    </form>
</body>

</html>

```