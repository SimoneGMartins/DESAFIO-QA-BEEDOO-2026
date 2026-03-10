# DESAFIO-QA-BEEDOO-2026
Desafio 2026 | Analista de Qualidade de Software Júnior
## Objetivo da aplicação

A aplicação tem como objetivo permitir o gerenciamento de cursos por meio de um formulário de cadastro e uma listagem dos cursos cadastrados.

O sistema possibilita ao usuário registrar informações sobre um curso, como título, descrição, URL da capa e link do curso, exibindo posteriormente esses cursos em uma lista na interface da aplicação.
## Principais fluxos da aplicação

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

### Cadastro de curso
O usuário preenche os campos do formulário com as informações do curso e realiza o cadastro através do botão "Cadastrar Curso".

### Listagem de cursos
Após o cadastro, os cursos são exibidos em uma lista na interface da aplicação.

### Exclusão de curso
O usuário pode remover um curso da lista através da opção de exclusão disponível na interface.

## Pontos críticos para teste

Durante a análise da aplicação foram identificados alguns pontos críticos que merecem maior atenção durante os testes:

- Validação de campos obrigatórios no formulário de cadastro
- Integridade das informações cadastradas
- Exibição correta dos cursos na listagem

## Cenários e Casos de Teste

Com base na análise realizada, foram criados cenários de teste para validar o funcionamento do módulo de cursos.

Os cenários incluem:

- Fluxo principal de cadastro de curso
- Verificação da listagem de cursos
- Cenários negativos
- Validações de campos
- Testes de comportamentos inesperados
- Funcionamento da funcionalidade de exclusão de cursos

Os casos de teste foram documentados na seguinte planilha:

[https://docs.google.com/spreadsheets/d/157xRT4FmdjF71hGAI5nYER3MgYBKMdaulhu-u0JWxxM/edit?usp=sharing]
## Execução dos testes

Os cenários de teste foram executados manualmente na aplicação.

Durante a execução foram registrados:

- Resultado obtido em cada teste
- Evidências da execução (prints de tela)
- Observações relevantes sobre o comportamento do sistema
As evidências da execução dos testes podem ser acessadas no link abaixo:

[https://drive.google.com/drive/folders/1k8fSqr-kwlIVN5HOnSUyLR2xQNhpbRGA?q=sharedwith:public%20parent:1k8fSqr-kwlIVN5HOnSUyLR2xQNhpbRGA]
## Bugs encontrados

Durante a execução dos testes foram identificados alguns comportamentos inesperados na aplicação, como:

- Cadastro de curso sem validação de campos obrigatórios
- Mensagem de sucesso no cadastro sem exibição do curso na listagem
- Funcionamento inconsistente da exclusão de cursos
- Falta de persistência dos dados após atualização da página

## Considerações finais

Durante a análise da aplicação foi possível identificar oportunidades de melhoria relacionadas principalmente à validação de dados, consistência das operações e persistência das informações cadastradas.

Os testes realizados buscaram cobrir tanto o fluxo principal da aplicação quanto cenários negativos e comportamentos inesperados, com o objetivo de avaliar a confiabilidade das funcionalidades disponíveis.

