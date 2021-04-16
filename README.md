# django-simples

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/leandro-matos/django-admin.git
cd django-admin
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser
```

```
docker run -p -d 8000:8000 leandromatpereira/django-admin:latest
```


### Deploy no Heroku: https://django-admin-leandro.herokuapp.com/
