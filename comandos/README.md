Iniciar o projeto Django

```
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin git@github.com:abreno76/projeto-agenda-django-23.git
git remote add origin https://github.com/abreno76/projeto-agenda-django-23.git
git push origin main -u
```