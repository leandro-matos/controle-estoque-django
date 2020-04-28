# Controle de estoque

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode o manage

```
git clone https://github.com/leandro-matos/controle-estoque-django.git
cd estoque
virtualenv venv
.\venv\Scripts\activate
pip install -r requirements.txt
cp .\contrib\env-sample .env
python3 manage.py runserver
