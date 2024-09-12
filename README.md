# estoque-de-loja
# Gerenciador de Estoque

Este projeto é um sistema simples para gerenciar o estoque de produtos usando arquivos CSV. O programa permite cadastrar produtos, atualizar estoque existente, exibir todos os produtos e remover produtos do estoque.

## Funcionalidades

- **Cadastrar Produto**: Adiciona um novo produto ao estoque ou atualiza a quantidade de um produto existente.
- **Exibir Produtos**: Lista todos os produtos no estoque com suas respectivas quantidades.
- **Remover Produto**: Remove um produto do estoque pelo código.

## Como Usar

1. **Cadastrar Produto**: Chame a função `cadastrar_produto()` para adicionar ou atualizar um produto no estoque.
2. **Exibir Produtos**: Chame a função `exibir_produtos()` para listar todos os produtos no estoque.
3. **Remover Produto**: Chame a função `remover_produto()` para remover um produto do estoque pelo código.

### Exemplo de Uso

```python
from estoque import cadastrar_produto, exibir_produtos, remover_produto

cadastrar_produto()
exibir_produtos()
remover_produto()
