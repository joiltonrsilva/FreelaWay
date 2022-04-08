# PyStack Week 3.0 | FreelaWay

Sistema de cadastro e pesquisa de vagas de emprego.

## Tecnologias e práticas utilizadas
- Python
- Django 4
- SQLite

## Funcionalidade
- Autenticação e Cadastro de Usuários

###

![alt text](https://raw.githubusercontent.com/samuel-oldra/PyStack-Week-3.0/main/README_IMGS/inscreva-se.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/PyStack-Week-3.0/main/README_IMGS/logar.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/PyStack-Week-3.0/main/README_IMGS/encontrar_jobs.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/PyStack-Week-3.0/main/README_IMGS/encontrar_jobs-detalhes.png)

## Comandos

### pip
```
pip list --outdate
python -m pip install --upgrade pip
python -m pip install --upgrade setuptools
```

### virtualenv (windows)
```
python -m venv env
env\Scripts\activate.bat
env\Scripts\deactivate.bat
```

### Instalar bibliotecas, gravar/instalar requerimentos
```
(env) pip install django
(env) pip install pillow

(env) pip freeze > requirements.txt
(env) pip install -r requirements.txt
```

### Criar projeto
```
(env) django-admin startproject freelaway .
```

### Criar apps
```
(env) python manage.py startapp autenticacao
(env) python manage.py startapp jobs
```

### Migrations
```
(env) python manage.py makemigrations
(env) python manage.py migrate
```
### Executar projeto
```
(env) python manage.py runserver
```
