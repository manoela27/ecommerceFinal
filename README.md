
# Ecommerce com Flask

Este é um Ecommerce desenvolvido com Flask. Permite aos usuários publicar produtos.

## Funcionalidades

- Criação, visualização e gerenciamento de produtos
- Interface estilizada com Bootstrap

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
├── templates
│   ├── index.html          # Template da página principal
│   ├── add_product.html    # emplate da página de criação de anúncios
│   ├── search_results.html  # Template da página para busca
│   ├── criar_anuncio.html  # Template da página de criação de anúncios
│   └── update_product.html  # Template da página para upar produto
...
```

Este projeto é destinado a avaliação de exame da disciplina de Frameworks do professor Diogo. 
