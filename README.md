
# Ecommerce com Flask

Este é um Ecommerce desenvolvido com Flask. Permite aos usuários criar contas, fazer login, publicar anúncios e visualizar um relatório de vendas. Este projeto é ideal para aqueles que desejam aprender ou desenvolver suas habilidades com Flask e desenvolvimento web em Python.

## Funcionalidades

- Registro e login de usuários
- Criação, visualização e gerenciamento de anúncios
- Relatórios de vendas
- Interface estilizada com Bootstrap
- Armazenamento de dados em memória

## Tecnologias Utilizadas

- [Flask](https://flask.palletsprojects.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Python](https://www.python.org/)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Linux e macOS
   venv\Scripts\activate     # Para Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Como Usar

1. Execute a aplicação:
   ```bash
   python app.py
   ```

2. Abra seu navegador e acesse:
   ```
   http://127.0.0.1:5000
   ```

## Estrutura do Projeto

```
.
├── app.py                  # Arquivo principal da aplicação Flask
├── models
│   ├── usuario.py          # Funções relacionadas a usuários
│   ├── anuncio.py          # Funções relacionadas a anúncios
│   └── relatorio.py        # Funções relacionadas a relatórios de vendas
├── templates
│   ├── index.html          # Template da página principal
│   ├── login.html          # Template da página de login
│   ├── meu_perfil.html     # Template da página de perfil do usuário
│   ├── meus_anuncios.html  # Template da página de anúncios do usuário
│   ├── criar_anuncio.html  # Template da página de criação de anúncios
│   └── relatorio_vendas.html  # Template da página de relatório de vendas
...
```

Este projeto é destinado a avaliação de exame da disciplina de Frameworks do professor Diogo. 
