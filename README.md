# 📝 Todo List App
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

Um aplicativo simples de lista de tarefas desenvolvido em Python utilizando o framework Django.


## Requisitos

- [![Python](https://img.shields.io/badge/Python-3.10.1-blue.svg)](https://www.python.org/)
- [![Django](https://img.shields.io/badge/Django-5.0.6-green.svg)](https://www.djangoproject.com/)

## Configuração do Ambiente Virtual

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/todo-list-app.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd todo-list-app
   ```

3. Crie um ambiente virtual:
   ```
   python -m venv venv
   ```

4. Ative o ambiente virtual:
   - No Windows:
     ```
     venv\Scripts\activate
     ```
   - No macOS e Linux:
     ```
     source venv/bin/activate
     ```

5. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```

## Configuração do Banco de Dados

1. Execute as migrações do Django:
   ```
   python manage.py migrate
   ```

## Execução do Servidor

1. Inicie o servidor de desenvolvimento:
   ```
   python manage.py runserver
   ```

2. Acesse o aplicativo em seu navegador web em `http://127.0.0.1:8000/`.

## Contribuindo

Sinta-se à vontade para enviar pull requests ou relatar problemas.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Este README fornece instruções básicas para configurar e executar o projeto em um ambiente local. Certifique-se de atualizar as seções conforme necessário com informações específicas do seu projeto, como a estrutura do banco de dados, funcionalidades adicionais e qualquer outra configuração relevante.