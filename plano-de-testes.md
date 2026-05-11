# PLANO DE TESTE — SAUCEDEMO

## 1. OBJETIVO

Garantir que as funcionalidades principais do sistema SauceDemo estejam funcionando corretamente, validando fluxo de login, navegação de produtos, carrinho e checkout.

---

## 2. ESCOPO DOS TESTES

Funcionalidades que serão testadas:

- Login
- Lista de produtos
- Filtro de produtos
- Carrinho
- Checkout
- Logout

---

## 3. TIPOS DE TESTE

- Teste funcional
- Teste de validação
- Teste de interface

---

## 4. AMBIENTE DE TESTE

**Sistema:**  
SauceDemo

**URL:**  
https://www.saucedemo.com

**Navegador:**  
Google Chrome

**Sistema Operacional:**  
Windows

---

## 5. DADOS DE TESTE

### Usuário válido
- standard_user

### Senha válida
- secret_sauce

### Usuário inválido
- usuario_invalido

### Senha inválida
- senha_invalida

---

## 6. FUNCIONALIDADES E CENÁRIOS

### LOGIN

#### Cenários:
- Login com dados válidos
- Login com usuário inválido
- Login com senha inválida
- Campos vazios
- Exibição de mensagem de erro

---

### PRODUTOS

#### Cenários:
- Visualizar lista de produtos
- Adicionar produto ao carrinho
- Remover produto
- Abrir detalhes do produto
- Utilizar filtro de ordenação

---

### CARRINHO

#### Cenários:
- Visualizar produtos adicionados
- Remover item do carrinho
- Validar quantidade de itens
- Continuar compra

---

### CHECKOUT

#### Cenários
- Checkout com carrinho vazio 
- Checkout com dados válidos
- Campos obrigatórios vazios
- Cancelar checkout
- Finalizar compra

---

### LOGOUT

#### Cenários:
- Realizar logout pelo menu lateral
- Validar retorno para tela de login

---

## 7. CRITÉRIOS DE ENTRADA

- Sistema disponível
- Navegador funcionando
- Credenciais válidas disponíveis

---

## 8. CRITÉRIOS DE SAÍDA

- Todos os cenários executados
- Bugs críticos documentados
- Fluxos principais funcionando corretamente

---

## 9. RISCOS

- Instabilidade do ambiente demo
- Lentidão do navegador
- Dados temporários do sistema

---

## 10. EVIDÊNCIAS

Serão coletados:

- Prints de tela
- Capturas de bugs
- Evidências de execução dos testes

---

## 11. RESULTADO ESPERADO

O sistema deve:

- Permitir login válido
- Impedir acessos inválidos
- Gerenciar corretamente produtos e carrinho
- Finalizar checkout sem erros
- Exibir mensagens apropriadas ao usuário
