# 🐍 API de E-commerce com Flask — Curso Rocketseat 🚀

Este projeto foi desenvolvido durante o **curso gratuito de Python com Flask da [Rocketseat](https://www.rocketseat.com.br/)**.  
O objetivo é criar uma **API completa** que simula um sistema de e-commerce, aplicando conceitos fundamentais de desenvolvimento web com Flask.

---

## 🧠 O que você vai aprender

Durante o curso, você aprenderá a:

- 🛠️ Criar e gerenciar **rotas** com Flask  
- 🧩 Integrar e manipular um **banco de dados** com SQLAlchemy  
- 🔐 Implementar **autenticação de usuário** com Flask-Login  
- 🛍️ Listar produtos, adicionar itens ao carrinho e realizar o checkout  
- 🌐 Trabalhar com **CORS** e boas práticas de APIs REST  
- 💾 Estruturar um projeto Flask de forma limpa e reutilizável  

Este é um projeto **perfeito para quem deseja iniciar no desenvolvimento web com Flask**, construindo uma base sólida para aplicações reais em Python.

---

## 🚀 Como rodar o projeto localmente

### 1. Clone o repositório
```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
cd nome-do-repositorio

2. Crie um ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate         # Windows

3. Instale as dependências
pip install -r requirements.txt

4. Crie o banco de dados

>>> from application import db
>>> db.create_all()
>>> exit()

5. Inicie a aplicação
python application.py


🧰 Tecnologias Utilizadas

Python

Flask

Flask-SQLAlchemy

Flask-Login

Flask-CORS