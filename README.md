# Diario Online - Pythonando 2

## Como Instalar

No terminal

```
python -m venv venv

source venv/bin/activate # Linux

venv/Scripts/activate # Windows

pip install -r requirements.txt
```

## Como executar

```
python manage.py makemigrations

python manage.py migrate

python manage.py runserver
```

## Criar ADM User

```
$ python manage.py createsuperuser
```

- Acesso Admin - http://127.0.0.1:8000/admin
- Startar server Diário - http://127.0.0.1:8000
