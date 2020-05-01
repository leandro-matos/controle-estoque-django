Controle de estoque

## Como rodar o projeto em sua máquina ?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências necessárias.
* Rode as migrações.

```
git clone https://github.com/leandro-matos/controle-estoque-django.git
cd controle-estoque-django
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
