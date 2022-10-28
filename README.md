# Viskiflix
Clone da netflix feito com o Django

## Funções
O usuario pode fazer as seguintes coisas:

- O usuário pode ver os diferentes tipos de filmes, series e documentarios disponiveis.
- O usuário pode ver a descrição os episódios e a quantidade de vizualização do filme.
- O usuário pode ver o Trailer ou um Edit do filme e sair e o filme estará na aba de Continuar Assistindo.

## Instalações / Configuração 
O aplicativo requer as seguintes instalações para funcionar:
- pip
- gunicorn
- django
- AWS
- requests

## Tecnologia Usada
- python 3.10.8

## Instruções de configuração do projeto
1) git clone the repository 
```
https://github.com/steve-njuguna-kDjango-Netflix-Clone.git
```
2. cd into Django-Netflix-Clone
```
cd Django-Netflix-Clone
```
3. create a virtual env
```
py -m venv env
```
4. activate env
```
env\scripts\activate
```
5. Open CMD & Install Dependancies
```
pip install -r requirements.txt
```
6. Make Migrations
```
py manage.py makemigrations
```
7. Migrate DB
```
py manage.py migrate
```
8. Run Application
```
py manage.py runserver
```
