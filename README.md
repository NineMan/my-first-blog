О приложении
============

Это код моего [блога](https://ninetest.pythonanywhere.com/), который запущен на [pythonanywhere](https://www.pythonanywhere.com/)


Run
----
1. ...
2. ...
3. ...


ToDo:
-----
1. Вынести secret_key
2. Сделать теги - чтобы удобно фильтровать по тегам.
3. Сделать удобную форму для редактирования текста статей.
4. Сделать форму регистрации (чтобы сторонние могли писать комменты)
5. Сделать удобную форму для редактирования текста статей.
6. Сделать автодеплой на сервер, например [вот так](https://stackoverflow.com/questions/48047123/syncing-github-with-pythonanywhere)


Deploy
----------------

1. Залить коммит на гитлаб.
```
git add ...
git commit -m "..."
git git push
```

2. консоли на pythonanywhere сделать 
```
git pull origin master
```

3. В Pythonanywhere -> Web нажать Reload