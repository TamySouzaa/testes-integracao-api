# Casos de Teste de Integração

## CT01 - Pagamento aprovado

Objetivo:
Validar a criação do pedido quando a API de pagamento aprova a transação.

Resultado esperado:
Pedido criado com sucesso.

---

## CT02 - Pagamento recusado

Objetivo:
Validar o comportamento quando a API retorna pagamento recusado.

Resultado esperado:
Pedido não criado e mensagem de erro exibida.

---

## CT03 - Timeout da API

Objetivo:
Validar o tratamento de timeout na comunicação.

Resultado esperado:
Sistema exibe mensagem de indisponibilidade.

---

## CT04 - Erro de autenticação

Objetivo:
Validar acesso utilizando token inválido.

Resultado esperado:
Retorno HTTP 401.

---

## CT05 - Resposta inválida da API

Objetivo:
Validar tratamento de payload inconsistente.

Resultado esperado:
Erro registrado e transação cancelada.
