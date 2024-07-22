# Dicionário de Dados

## Entidade Motivo

| Variável  | Nome da variável | Tipo da variável | Descrição                                                                                                | Valores permitidos | Possui valores nulos | É chave |
| --------- | ---------------- | ---------------- | -------------------------------------------------------------------------------------------------------- | ------------------ | -------------------- | ------- |
| Descrição | descricao        | char[1000]       | A variável Descrição apresenta os motivos do aluno para querer realizar a Revisão de Mensão da diciplina | a-z, A-Z           | Não                  | Não     |

## Entidade Solicitação

| Variável  |  Nome da variável  |  Tipo da variável  |  Descrição  |  Valores permitidos  |  Possui valores nulos  |  É chave |
| --- | --- | --- | --- | --- | --- | ---|
| Código da diciplina | codigo_dic | char[8] | O Cóldigo da Diciplina apresenta uma reunião de números e letras que representam a diciplina e que não será repetido por nenhuma outra diciplina | a-z, A-Z, 000-999 | Sim | Sim |