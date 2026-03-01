# Confeitaria API

API desenvolvida em Flask que conecta ao PostgreSQL e retorna o cardápio em formato JSON.

## Tecnologias
- Python
- Flask
- PostgreSQL
- psycopg2

## Rota principal

GET /cardapio  
Retorna todos os itens da tabela `cardapio`.

Exemplo de resposta:

[
  {
    "id": 1,
    "titulo": "Bolo de Chocolate",
    "descricao": "Clássico e fofinho",
    "foto": "https://..."
  }
]

## Como rodar

1. Instalar dependências:
pip install -r requirements.txt

2. Configurar variáveis no arquivo `.env`

3. Rodar:
python main.py