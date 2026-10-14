# Carros

Aplicação web em Django para listagem e visualização de veículos, com autenticação de usuários. Foi feita a partir de um curso de Django, e eu configurei o deploy em um servidor Linux na AWS EC2.

# Midia do projeto

<img width="1917" height="866" alt="Captura de tela 2026-10-13 221549" src="https://github.com/user-attachments/assets/238b6e8d-d71a-47ad-8bf9-fc772040389f" />
<img width="1917" height="863" alt="Captura de tela 2026-10-13 222825" src="https://github.com/user-attachments/assets/b3220a10-0d2b-4a0e-9cb4-c44bd4e4b13b" />
<img width="1917" height="861" alt="Captura de tela 2026-10-13 222847" src="https://github.com/user-attachments/assets/c4fb8c52-bcb8-48dc-bc70-7b86056c9201" />
<img width="1917" height="863" alt="Captura de tela 2026-10-13 222905" src="https://github.com/user-attachments/assets/b4b08e9b-02be-418f-a07d-f5e09a7f12d8" />



## Tecnologias

Python, Django,PostgreSQL, HTML e CSS, AWS EC2.

## Funcionalidades

Listagem de veículos, página de detalhes de cada carro, cadastro e login de usuários (app accounts) e painel admin.

## Deploy

Publicado em um servidor Linux na AWS EC2. O ambiente está desativado, mas o código completo está neste repositório.

## Como rodar localmente

git clone https://github.com/ramoos05/carros.git
cd carros

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver

## Estrutura

carros/
  accounts/   autenticação de usuários
  app/        configurações do projeto
  cars/       app dos veículos
  manage.py
  requirements.txt

## Aprendizados

Deploy de uma aplicação Django em servidor cloud, configuração de ambiente virtual e dependências, organização de projeto em apps.

## Autor

Patrick Ramos
