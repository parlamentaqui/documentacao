# Earned Value Management

| Data       | Versão | Descrição                                           | Autor              |
| ---------- | ------ | --------------------------------------------------- | ------------------ |
| 22/03/2021 | 0.1    | Adicionado template               | Gabriel Albino |

## Descrição
Esse documento tem como objetivo gerenciar e rastrear o retorno do investimento do produto Parlamentaqui

## Legenda

**Story points**: Pontos de estória.

**PMB - Performance Measurement Baseline e PRP - Planned Release Points**: Numero total de story points planejados para a release.

**Schedule Baseline**: O número total de sprints planejadas (PS) multiplicado pelo
comprimento do sprint.

**BAC - Budget at Complete**: O orçamento planejado para o lançamento.

**PPC - Planned Percent Complete**: O número do sprint atual (n) dividido pelo número total de sprints planejados (PS).

**APC - Actual Percent Complete**: O número total de story points concluídos dividido pelo número total de story points planejados.

**L - Sprint Length**: Duração da sprint em dias.

**PS - Planned Sprints**: O numero total de sprints planejadas para a release.

**SD - Starting Date**: Data do inicio da release

**n - Sprint number**: Numero da sprint atual.

**PC - Points Completed**: Pontos do backlog completados durante a sprint

**PA - Points Added**: Pontos adicionados do backlog durante a sprint

**SC - Sprint Cost**: quanto foi gasto durante a sprint (calculado como BAC/PS)

**RPC - Release Points Completed:**: Quantos story points estavam completos na sprint.

**APC - Actual Percent Complete of Release**: Percentual de pontos realizados em relação aos pontos planejados.

**PPC - Planned percent complete.**: Percentual de sprints decorridas em relação ás sprints planejadas


## Release 1 (MVP)
A release 1, composta pelas ondas 1 e 2 do [lean inception](./lean_inception.md) e com as estórias descritas no [detalhamento da Release 1 no backlog](./backlog.md#Detalhamento-por-Release), contem os seguintes parâmetros: 

### BAC - Budget at Complete
Para o calculo do BAC foi levado em conta 3 fatores, descritos abaixo:

**1. Preço da mão de obra de cada aluno da UnB envolvido no projeto**
Para realizar esse calculo, foi utilizado o valor médio de custo por aluno de 15 mil reais/ano, conforme publicado em [matéria do correio braziliense](https://www.correiobraziliense.com.br/app/noticia/eu-estudante/ensino_ensinosuperior/2015/03/05/ensino_ensinosuperior_interna,474102/portas-abertas-ao-cidadao). A matéria não cita fontes porém não foram encontrados outros locais com a informação.

Considerando que o ano possui 2 semestres letivos, e considerando uma média de 360 horas/aula realizada por aluno a cada semestre, chegamos ao valor aproximado de 20 reais/hora.

Considerando o tempo de dedicação de 10 horas/sprint ao projeto, temos um custo por membro de 200 reais por sprint, totalizando 2000 reais/sprint para todo o time.

Levando em conta as 5 sprints com histórias de usuário estimadas, chegamos ao valor de 8000 reais de mão de obra para a release 1.

**2. Custos de serviços de energia e internet**

a) Energia

Considerando o consumo de 60 Watts/hora por notebook e levando em conta as mesmas 10 horas de desenvolvimento/sprint, chegamos ao valor de 600 Watts/sprint por membro, totalizando 6000 Watts/sprint para toda a equipe.
Considerando o valor de R$0,52/Watt divulgado pela [DME Energética](http://www.dme-pc.com.br/atendimento/tarifas), chegamos ao custo de energia de R$ 312,00/sprint.

b) Internet

Para o custo de serviço de internet, será considerado o valor de R$100/mes para cada membro, totalizando uma média de R$250/sprint para todos os membros do projeto.

**Custo total de serviços de energia e internet**

Com esses valores definidos, chegamos ao valor de R$562,00/sprint, totalizando um custo total de R$2248,00 para a release 1.

**3. Custos de servidores e acessos de APIs.**
Não utilizaremos nenhum serviço pago para o projeto, teremos apenas um custo inicial de DNS, consideraremos 50 reais para todo a release.


**Custo total da release**
Somando todos os critérios estabelecidos acima, chegamos ao Budget at Complete de **R$10298**.

### L - Sprint Length
A duração da sprint definida para todo o produto foi de 7 dias.

### PS - Planned Sprints
Para a release 1 foram planejadas 5 sprints com pontos no total, o detalhamento pode ser visto no [cronograma do produto](./cronograma_do_produto.md)

### SD - Starting Date
A data de inicio da release 01 foi definida como dia 01/03/2020.

### PRP - Planned Release Points
De acordo com o [detalhamento da Release 1 no backlog](./backlog.md#Detalhamento-por-Release), a release 1 conta com 157 story points.

### Parâmetros iniciais da release
|BAC|L|PS|SD|PRP_0|
|-|-|-|-|-|
|R$10298|7|5|07/03/2020|157|

### Sprints (WORK IN PROGRESS)

|n|AC|PC|PA|SC|PRP|RPC|APC|PPC|PV|EV|CV|SV|CPI|SPI|ETC|EAC|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|1|X|X|X|X|X|X|X|0.2|X|X|X|X|X|X|X|X|
|2|X|X|X|X|X|X|X|0.4|X|X|X|X|X|X|X|X|
|3|X|X|X|X|X|X|X|0.6|X|X|X|X|X|X|X|X|
|4|X|X|X|X|X|X|X|0.8|X|X|X|X|X|X|X|X|
|5|X|X|X|X|X|X|X|1.0|X|X|X|X|X|X|X|X|

### Detalhamento das sprints
Veja mais detalhes sobre as estórias de usuário no [backlog](./backlog.md). Perceba que, para o EVM foi utilizado um offset de 5 sprints, portanto a sprint 1 do EVM corresponde a sprint 6 do backlog.

**Sprint 1**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US45 e US42|16|13|-3|13|[issue #2](https://github.com/parlamentaqui/frontend/issues/2)|
|US04|13|5|-8|5|[issue #7](https://github.com/parlamentaqui/frontend/issues/7)|
|US40|5|13|+8|0|[issue #3](https://github.com/parlamentaqui/frontend/issues/3)|
|US46|5|8|+3|8|[issue #8](https://github.com/parlamentaqui/frontend/issues/8)
|TOTAL|39|39|0|26||

**Sprint 2**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US40|N/A|N/A|0|0|Dívida técnica não entregue([issue #3](https://github.com/parlamentaqui/frontend/issues/3))|
|US41|8|||||


**Sprint 3**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US01|8|||||
|US02|8|||||
|US09|8|||||
|US03|8|||||
|US38|8|||||
|US37|8|||||
|US39|8|||||
|TOTAL|39|39|0|26||