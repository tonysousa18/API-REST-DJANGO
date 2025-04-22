# 📚 Django Books API

Este projeto é uma API RESTful simples desenvolvida com Django e Django REST Framework para gerenciar um acervo de livros. Ela permite criar, listar, atualizar e deletar informações sobre livros como título, autor, ano de lançamento, número de páginas e editora.

## 🚀 Tecnologias Utilizadas

- Python 3
- Django 4.x
- Django REST Framework


## 📦 Endpoints

A API possui os seguintes endpoints disponíveis após iniciar o servidor:

| Método | Endpoint       | Descrição                      |
|--------|----------------|--------------------------------|
| GET    | `/books/`      | Lista todos os livros          |
| POST   | `/books/`      | Cria um novo livro             |
| GET    | `/books/<id>/` | Detalha um livro específico    |
| PUT    | `/books/<id>/` | Atualiza todos os dados        |
| PATCH  | `/books/<id>/` | Atualiza parcialmente          |
| DELETE | `/books/<id>/` | Remove um livro do acervo      |

## 🛠 Como Executar Localmente
- Clone o repositório:
git clone https://github.com/tonysousa18/API-REST-DJANGO.git
cd books-api

- Crie um ambiente virtual:
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows


- Instale as dependências:
pip install -r requirements.txt

- Execute as migrações:
python manage.py migrate

- Inicie o servidor de desenvolvimento:
python manage.py runserver

