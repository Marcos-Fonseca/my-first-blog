my-first-blog
=============
projeto do tutorial de django girls - https://tutorial.djangogirls.org/pt/

Requisitos:
-----------
* python 3.6 ou superior


##### OBS: instrucoes especificas para sistemas operacionais linux

Para executar o projeto, clone ele e crie um ambiente virtual
```console
$ python -m venv venv
```
depois ative o ambiente virtual
```console
$ source venv/bin/activate
```

entre na pasta **my-first-blog** e execute os seguintes comandos
```console
# pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py runserver
```

abra o navegador e digite o endereço **http://127.0.0.1:8000/** no campo de urls
