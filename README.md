# 🚗 Carros - Aplicação Web com Django

Aplicação web desenvolvida com Django para listagem e visualização de veículos, com deploy em ambiente real (AWS). O projeto simula um sistema de catálogo automotivo e foi construído com foco em boas práticas de backend.

---

## 📌 Sobre o Projeto

O **Carros** é uma aplicação backend que permite listar veículos e visualizar suas informações, servindo como base para sistemas maiores como marketplaces ou plataformas de revenda.

Este projeto foi desenvolvido com foco em aprendizado prático de desenvolvimento web com Django e experiência com deploy em produção.

---

## 🚀 Tecnologias Utilizadas

* Python
* Django
* SQLite / PostgreSQL
* HTML / CSS
* AWS (EC2)

---

## ⚙️ Funcionalidades

* 📋 Listagem de veículos
* 🔎 Visualização de detalhes dos carros
* 🧱 Estrutura modular com Django
* 🌐 Deploy em ambiente de produção

---

## 🖥️ Demonstração

A aplicação está disponível online:

👉 http://54.161.166.153/cars/

---

## 🛠️ Como rodar o projeto localmente

```bash
# Clone o repositório
git clone https://github.com/ramoos05/carros.git

# Acesse a pasta
cd carros

# Crie um ambiente virtual
python -m venv venv

# Ative o ambiente virtual (Windows)
venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações
python manage.py migrate

# Inicie o servidor
python manage.py runserver
```

---

## 📁 Estrutura do Projeto

```
carros/
│
├── cars/            # App responsável pelos veículos
├── core/            # Configurações principais do projeto
├── manage.py
└── requirements.txt
```

---

## 🧠 Decisões Técnicas

* Utilização do Django pela sua estrutura robusta e produtividade
* Organização do projeto em apps para melhor separação de responsabilidades
* Deploy em AWS EC2 para simular ambiente de produção real

---

## 📚 Aprendizados

* Deploy de aplicação Django em servidor cloud (AWS)
* Configuração de ambiente virtual e dependências
* Estruturação de projetos com Django
* Integração com banco de dados

---

## 👨‍💻 Autor

Desenvolvido por Patrick Ramos
