# API de Chamados de Suporte

**ALUNO:** Antonio Lucas da Costa Pereira

## Objetivo

Desenvolver a estrutura inicial de uma API REST utilizando Python e Flask, como parte da atividade prática de criação da primeira API. Nesta etapa, a aplicação disponibiliza uma rota inicial para verificar seu funcionamento.

## Tecnologias utilizadas

- Python
- Flask
- uv

## Instalação das dependências

Com o repositório aberto no terminal, execute:

```bash
uv sync --locked
```

## Execução da aplicação

Para iniciar o servidor Flask, execute:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Rota disponível

| Método | Rota | Descrição |
|---|---|---|
| GET | `/` | Verifica se a API está em funcionamento. |

## Resposta esperada

Ao acessar a rota inicial, a API deverá retornar o status HTTP `200` e o seguinte objeto JSON:

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```

## Acesso à aplicação

Com o servidor em execução, acesse:

```text
http://localhost:5000/
```

No GitHub Codespaces, também é possível acessar a aplicação pela porta `5000`, disponibilizada na aba **Ports**.