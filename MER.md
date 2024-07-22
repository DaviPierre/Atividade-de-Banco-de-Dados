# Modelo Entidade Relacionamento 

## Legenda

<center>

| Definição         | Sigla |
| ----------------- | ----- |
| Chave primária    | CP    |
| Chave estrangeira | CE    |

</center>

## Entidades

### Motivo

  - descricao

### Solicitação 

-  codigo_dic CP 
-  diciplina
-  turma
-  periodo
-  professor

### Identificacao

- matricula CP
- nome
- curso
- n_cursdo
- faculdade
- departamento
- turno
- nivel
  
### Contato

- email
- telefone
- celular

### Situação

- opcao

## Relacionamento

### Solicitação VS Motivo

- Solicitação possui um Motivo
- Motivo é possuído por uma Solicitação

### Solicitação VS Identificação

- Identificação realiza várias (n) Solicitações
- Solicitações são realizadas por uma Identificação 

### Identificação VS Situação

  - Identificação possui uma Situação
  - Situação é possuido por várias (n) Identificações

### Identificação VS Contato

- Identificação possui 1 contato
- Contato é possuido por 1 Identificação
