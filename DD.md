# Dicionário de Dados

## Entidade Motivo

| Variável  | Nome da variável | Tipo da variável | Descrição                                                                                                | Valores permitidos | Possui valores nulos | É chave |
| --------- | ---------------- | ---------------- | -------------------------------------------------------------------------------------------------------- | ------------------ | -------------------- | ------- |
| Descrição | descricao        | char[1000]       | A variável Descrição apresenta os motivos do aluno para querer realizar a Revisão de Mensão da diciplina | a-z, A-Z           | Não                  | Não     |

## Entidade Solicitação

| Variável            | Nome da variável | Tipo da variável | Descrição                                                                                                                                        | Valores permitidos  | Possui valores nulos | É chave |
| ------------------- | ---------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------- | -------------------- | ------- |
| Código da diciplina | codigo_dic       | char[8]          | O Cóldigo da Diciplina apresenta uma reunião de números e letras que representam a diciplina e que não será repetido por nenhuma outra diciplina | a-z, A-Z, 000-999   | Não                  | Sim     |
| Diciplina           | diciplina        | char[20]         | A Diciplina representa o nome da diciplina na qual a solicitação está sendo feita                                                                | a-z, A-Z, 1-3       | Não                  | Não     |
| Truma               | turma            | int              | A Turma representa qual turma específica dentro de uma diciplina o aluno está se referindo                                                       | 1-10                | Não                  | Não     |
| Período             | periodo          | char[5]          | O Período se refere ao horário que o aluno está cursando a Diciplina                                                                             | manhã, tarde, noite | Não                  | Não     |
| Professor           | professor        | char[100]        | O Professor se refere ao responsável pela diciplina específica da turma específica que o aluno está se referindo                                 | a-z, A-Z            | Não                  | Não     |

## Entidade identificação

| Variável        | Nome da variável | Tipo da variável | Descrição                                                                                                                             | Valores permitidos    | Possui valores nulos | É chave |
| --------------- | ---------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | -------------------- | ------- |
| Matrícula       | matricula        | int              | A Matrícula é uma idenficação do aluno que não será repetida nunca, composta por números começando pelo ano que o aluno se matriculou | 000000001 - 999999999 | Não                  | Sim     |
| Nome            | nome             | char[100]        | O Nome representa o nome do aluno                                                                                                     | a-z, A-Z              | Não                  | Não     |
| Curso           | curso            | char [150]       | O Curso representa qual curso o aluno está cursando                                                                                   | a-z, A-Z              | Não                  | Não     |
| Número do Curso | n_curso          | int              | O Número do curso é um conjunto de números que irá identificar a qual curso o aluno pertence                                          | 000000000-999999999   | Não                  | Não     |
| Faculdade       | faculdade        | char[100]        | A Faculdade é uma variável que vai definir em qual instituição de ensino superior o aluno estuda                                      | a-z, A-Z              | Não                  | Não     |
| Departamento    | departametno     | char[100]        | O Departamento identifica qual departamento o aluno pertence                                                                          | a-z, A-Z              | Não                  | Não     |
| Turno           | turno            | char[10]         | O turno vai definir qual o horário de estudo do aluno dentro da faculdade                                                             | a-z, A-Z              | Não                  | Não     |
| Nível           | nivel            | int              | O Nível define em qual estágio da faculdade o aluno se encontra                                                                       | 1-16                  | Não                  | Não     |

## Entidade SItuação 

| Variável | Nome da variável | Tipo da variável | Descrição                                                                     | Valores permitidos | Possui valores nulos | É chave |
| -------- | ---------------- | ---------------- | ----------------------------------------------------------------------------- | ------------------ | -------------------- | ------- |
| Opção    | opcao            | int              | A Opção representa qual motivo é importante a negociação da Revisão de Mensão | 1-5                | Não                  | Não     |

## Entidade Contato 

| Variável           | Nome da variável | Tipo da variável | Descrição                                                                         | Valores permitidos    | Possui valores nulos | É chave |
| ------------------ | ---------------- | ---------------- | --------------------------------------------------------------------------------- | --------------------- | -------------------- | ------- |
| Email              | email            | char[100]        | O Email representa o entereço de correio digital do aluno                         | a-z                   | Não                  | Não     |
| Número de Telefone | telefone         | int              | O Número de Telefone representa o contato do telefone fíxo do aluno               | 0000000000-9999999999 | Sim                  | Não     |
| Número de Celular  | celular          | int              | O Número de Celular representa o contato do telefone pessoal/de trabalho do aluno | 0000000000-9999999999 | Não                  | Não     |
