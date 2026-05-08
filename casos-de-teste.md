# CT-001 — Login com credenciais válidas

## Prioridade
Alta

## Pré-condição
Usuário deve estar na página de login do SauceDemo.

## Passos
1. Inserir um usuário válido
2. Inserir uma senha válida
3. Clicar no botão "Login"

## Resultado esperado
O sistema deve permitir acesso à página de produtos.

## Resultado obtido
O sistema permitiu acesso corretamente à página de produtos.

## Evidência

![Login realizado com sucesso](evidencias/ct-001.png)

## Status
Aprovado

# CT-002 — Login com usuário inválido

## Prioridade
Alta

## Pré-condição
Usuário deve estar na página de login do SauceDemo.

## Passos
1. Inserir um usuário inválido
2. Inserir uma senha válida
3. Clicar no botão "Login"

## Resultado esperado
O sistema deve impedir o acesso e exibir uma mensagem de erro ao usuário.

## Resultado obtido
O sistema impediu o acesso corretamente e exibiu mensagem de erro.

Foi identificado um problema visual na mensagem de erro. 
Bug relacionado: BUG-001.

## Evidência

![Mensagem de erro no login](evidencias/ct-002.png)

## Status
Aprovado com observação

# CT-003 — Login com senha inválida

## Prioridade
Alta

## Pré-condição
Usuário deve estar na página de login do SauceDemo.

## Passos
1. Inserir um usuário válido
2. Inserir uma senha inválida
3.  Clicar no botão "Login"

## Resultado esperado
O sistema deve impedir o acesso e exibir uma mensagem de erro ao usuário.

## Resultado obtido
O sistema impediu o acesso corretamente e exibiu a mensagem de erro esperada.

Foi identificado o mesmo problema visual de CT-002.
Bug relacionado: BUG-001

## Evidência

![Senha inválida exibindo erro](evidencias/ct-003.png)

## Status
Aprovado com observação

# CT-004 — Login com campos vazios

## Prioridade
Alta

## Pré-condição
Usuário deve estar na página de login do SauceDemo.

## Passos
1. Deixar os campos de usuário e senha vazios
2. Clicar no botão "Login"

## Resultado esperado
O sistema deve impedir o acesso e exibir uma mensagem informando que os campos devem ser preenchidos.

## Resultado obtido
O sistema impediu o acesso corretamente e exibiu mensagem de erro corretamente.

## Evidência

![Campos vazios exibindo erro](evidencias/ct-004.png)

## Status
Aprovado
