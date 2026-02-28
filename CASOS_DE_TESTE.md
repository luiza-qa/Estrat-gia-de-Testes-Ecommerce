# 🧪 Casos de Teste: Fluxo de Compra e Checkout
**QA Responsável:** Luíza Silva

## CT-001: Validar adição de produto ao carrinho com sucesso
**Objetivo:** Garantir que um usuário logado consiga adicionar um item ao carrinho.
- **Pré-condição:** Usuário deve estar logado na plataforma.
- **Passos:**
  1. Pesquisar pelo produto "Tênis Esportivo".
  2. Selecionar o tamanho "37" e cor "Roxa".
  3. Clicar no botão "Adicionar ao Carrinho".
- **Resultado Esperado:** O sistema deve exibir a mensagem "Produto adicionado com sucesso" e o ícone do carrinho deve atualizar para "1 item".

## CT-002: Validar cálculo de frete no carrinho
**Objetivo:** Verificar se o sistema integra corretamente com a API de logística.
- **Passos:**
  1. Acessar a tela do carrinho.
  2. Inserir o CEP "01001-000".
  3. Clicar em "Calcular".
- **Resultado Esperado:** O valor do frete e o prazo de entrega devem ser exibidos conforme retorno da API via ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white).
