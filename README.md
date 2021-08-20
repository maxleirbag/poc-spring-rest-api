# spring-rest-api
Prova de conceito de aplicação destinada a receber Solicitações de Entrega, usando REST API e ecossistema Spring.

## Clientes (CRUD)
Métodos REST:

GET

Listar todos = /clientes
Buscar nome exato = /nome/nome_exato
Buscar nome parecido = /parecido/nome_parecido
Buscar id = /id/id_desejado
POST

Adicionar (JSON) = /clientes
(Strings = "nome"(60),"email"(i@i.algo, 255),"telefone"(20))
PUT

Atualizar (JSON) = /clientes/id_desejado
(Strings = "nome"(60),"email"(255),"telefone"(20))
DELETE

Deletar = /clientes/id_alvo

## Entregas

### Autorização de acesso

Ex.: data de finalização não autorizada:
![SQL Injection](https://user-images.githubusercontent.com/78800453/130260452-d5dc0b32-a25d-4aa9-b74d-424784be3066.png)

Prevenindo IDOR com SQL Injection:
![Denied](https://user-images.githubusercontent.com/78800453/130260528-cee87931-5afb-4362-9795-efe235da0a3d.png)


