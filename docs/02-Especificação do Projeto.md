# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem.

|IMAGEM|NOME| CARACTERÍSTICAS|
|--------------------|------------------------------------|----------------------------------------|
|  | Olívia Barbara de Jesus           | * Idade: 70 anos <br> * Ocupação: Aposentada <br> <b> Aplicativos: </b> <br> * WhatsApp <br> * Facebook <br> <b>Frustrações</b><br> * Letras muito pequenas;<br> * Falta de objetividade nas aplicações. <br> <b>Hobbies</b><br> * História;<br> * Jardinagem.|
|  | Thomas Ferreira           | * Idade: 75 anos <br> * Ocupação: Aposentado <br> <b> Aplicativos: </b> <br> * WhatsApp <br> <b>Frustrações</b><br> * Excesso de informação;<br> * Dificuldade de aprendizado. <br> <b>Hobbies</b><br> * História;<br> * Culinária.|

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Olívia Barbara de Jesus  | Quero um aplicativo de fácil uso para marcar minhas consultas           | Para conseguir usar o aplicativo sem precisar pedir ajuda.|
|Olívia Barbara de Jesus     | Quero um aplicativo que me auxilie a conseguir um transporte até a clínica                 | Para conseguir chegar facilmente até o local do atendimento. |
|Olívia Barbara de Jesus  | Quero consultas médicas com horários flexíveis na clínica           | Para poder agendar de acordo com meus compromissos e não ter que esperar muito tempo na sala de espera|
|Olívia Barbara de Jesus| Desejo uma equipe médica simpática e atenciosa na clínica                | Para me sentir confortável e compreendida durante minhas consultas e exames |
|Olívia Barbara de Jesus  | Quero instalações acessíveis na clínica, incluindo rampas e banheiros adaptados            | Para facilitar minha locomoção e garantir minha segurança|
|Thomas Ferreira | Desejo receber orientações prévias sobre preparos para exames online na clínica| Para acompanhar minha saúde de forma rápida e conveniente, sem precisar esperar por correspondências |
|Thomas Ferreira  | Quero agendar exames online na clínica| para evitar longas esperas e facilitar o planejamento dos meus compromissos|
|Thomas Ferreira | Quero acessar meus resultados de exames pela internet na clínica | Para não esquecer compromissos importantes e garantir minha presença nos horários marcados |
|Thomas Ferreira  | Quero poder acompanhar a disponibilidade de horários para consultas e exames online na clínica  | Para encontrar facilmente o melhor momento que se encaixe na minha agenda|
|Thomas Ferreira      | Quero receber orientações sobre transporte acessível até a clínica. | Para garantir que posso chegar lá de forma segura e sem dificuldades de locomoção |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que o usuário gerencie suas tarefas | ALTA | 
|RF-002| A aplicação deve emitir um relatório de tarefas realizadas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
