# Django

## Passos iniciais

Criação do ambiente virtual:

```
python -m venv myvenv
```

Para permitir a execução do ambiente virtual, digite o seguinte comando no powershell do Windows como administrador.

```
Set-Execution Policy - Scope CurrentUser -ExecutionPolicy RemoteSigned
```

Ativar o ambiente virtual:

```
.\myvenv\Scripts\activate.ps1
```

Sair do ambiente virtual:

```
deactivate
```

Atualizar pip:

```
python -m pip install --upgrade pip
```

Instalar django através do arquivo requirements.txt:

```
pip install -r requirements.txt
```

Criar projeto:

```
django-admin.exe startproject mysite .
```

python manage.py runserver

python manage.py startapp <app_name>

python manage.py makemigrations <app_name>

python manage.py migrate <app_name>

python manage.py createsuperuser

pa_autoconfigure_django.py --python=3.8 https://github.com/<your-github-username>/<your-github-repository>.git
