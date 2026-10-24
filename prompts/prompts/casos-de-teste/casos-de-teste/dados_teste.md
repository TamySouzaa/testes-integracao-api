# Dados de Teste

## Cenário 1

Valor:
R$ 100,00

Cartão:
4111111111111111

Resultado esperado:
Pagamento aprovado.

---

## Cenário 2

Valor:
R$ 100,00

Token:
INVÁLIDO

Resultado esperado:
HTTP 401

---

## Cenário 3

Número do cartão:
Vazio

Resultado esperado:
HTTP 400

---

## Cenário 4

Serviço indisponível

Resultado esperado:
HTTP 503

---

## Cenário 5

Timeout superior a 30 segundos

Resultado esperado:
Falha na integração.
