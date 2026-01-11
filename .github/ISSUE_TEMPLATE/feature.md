---
name: Feature
about: Nova funcionalidade
---

## Contexto
Descreva o cenário atual, o problema identificado e por que essa funcionalidade é necessária.

---

## Objetivo
Descrever claramente o que essa funcionalidade deve entregar ao sistema e qual problema ela resolve.

---

## Endpoint
- **Método:** (GET | POST | PUT | DELETE)
- **Caminho:** `/api/exemplo/{id}`

---

## Critérios de aceite

- [ ] (descreva)

---

## Retornos esperados

### Sucesso
- **200 OK | 201 Created | 204 No Content**
  - Descrever o retorno esperado em caso de sucesso (corpo da resposta ou ausência dele).

---

### Erros
- **400 Bad Request**  
  - Quando os dados enviados na requisição forem inválidos.
- **404 Not Found**  
  - Quando o recurso solicitado não for encontrado.
- **409 Conflict**  
  - Quando ocorrer conflito de dados ou violação de regra de negócio.
- **500 Internal Server Error**  
  - Para erros inesperados durante o processamento da requisição.

Todos os erros devem retornar mensagens claras e padronizadas e ser tratados via **Global Exception Handler**.

---

## Impactos / Dependências
Informar se essa feature depende de outra entrega ou se impacta funcionalidades existentes.  
- #ID_DA_ISSUE

---

## Observações
Informações adicionais relevantes, regras específicas, decisões técnicas ou pontos de atenção.
