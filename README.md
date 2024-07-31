# webDevHomeWork07_Django

---

Для установки mysqlclient:

https://pypi.org/project/mysqlclient/

mac os global environment run: ->

```
brew install mysql-client pkg-config
```

in your virtualenv or other environment ->

```
export PKG_CONFIG_PATH="$(brew --prefix)/opt/mysql-client/lib/pkgconfig"
```

```
pip install -r requirements.txt
```

---

Создание нового проекта:
```
django-admin startproject my_project_name .
```

Запуск сервера разработки:
```
python manage.py runserver 
```

Создание нового приложения:
```
python manage.py startapp my_app_name
```
