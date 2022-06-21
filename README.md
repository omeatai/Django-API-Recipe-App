# Django-API-Recipe-App

Django-API-Recipe-App Project By Ifeanyi Omeata

---

### [1-SETUP](#)

---

### 1. Create-ENV

```python
  pipenv shell
```

### 2. Install Django dependencies

```python
  pipenv install django djangorestframework django-shortcuts
```

### 3. Create Core Project

```python
  django-admin startproject coreproject .
```

### 4. Create Core App

```python
  python manage.py startapp core
```

### 5. Register Core App in Settings - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/923774964d24437b8399a77846bc901e71f4b868)

### 6. Install Autopep8

```python
  pipenv install autopep8
```

---

### [2-CREATE USER MODEL](#)

---

### 1. Test_create_user_with_email_successful - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/0f655a703c374b75b9874a0e641a4b7a0854f96b)

### 2. Create User and User Manager Models - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/3214f5252f3d85ee5b3a8a22f08d5db728ad24b4)

### 3. Django Make Migrations

```python
  python manage.py makemigrations
```

### 4. Django Migrate

```python
  python manage.py migrate
```
