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

### 5. Run Django Test

```python
  python manage.py test
```

### 6. Test_new_user_email_normalized - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/8a519dc854280b3e4b8ec00b658b281a1339c9c9)

### 7. Test_new_user_without_email_raises_error - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/94feda343f9e687b13a7b9a9f5cbddc71bed22e0)

### 8. Test_create_superuser - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/658169fa3787777e26164acb7fa3fbd5663e30a1)

### 9. Test_users_lists - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/25cd1011848308d1a8e65fe24e0ca19d9679a963)

### 10. Define the admin pages for users - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/aeab95a26eb124684e4e9ab135506a4b4dd23e6f)

### 11. Test_edit_user_page - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/d11d7b84d0694a9f9b587f89673c119e30cf4604)

### 12. Test_create_user_page - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/0894b4d76c7e0580b8f9a0ac6a2b6ef2a5ccada2)

---

### [3-CREATE USER API](#)

---

### 1. Create User App

```python
  python manage.py startapp user
```

### 2. Add User App and Rest Framework to settings - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/d81eeb5a6cac67ef010d2996e73d287a5073d3f7)

### 3. Test_create_user_api - [here](https://github.com/omeatai/Django-API-Recipe-App/commit/0796c8a5c5fecde6d662b37d90a054d3171fd4b8)

```python
  python manage.py test
```
