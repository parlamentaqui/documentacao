# EVM

## Earned Value Management

| Data       | Versão | Descrição                                           | Autor              |
| ---------- | ------ | --------------------------------------------------- | ------------------ |
| 22/03/2021 | 0.1    | Adicionado template                                 | Gabriel Albino     |
| 22/03/2021 | 0.2    | Adicionado parâmetros iniciais da release           | Gabriel Albino     |
| 23/03/2021 | 0.3    | Adicionado dados das sprints 1 e 2                  | Gabriel Albino     |
| 01/04/2021 | 1.0    | Adicionado dados da release 1              | Gabriel Albino     |
| 22/04/2021 | 1.1    | Adicionado dados do incremento 1              | Gabriel Albino     |

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

- Energia

Considerando o consumo de 60 Watts/hora por notebook e levando em conta as mesmas 10 horas de desenvolvimento/sprint, chegamos ao valor de 600 Watts/sprint por membro, totalizando 6000 Watts/sprint para toda a equipe.
Considerando o valor de R$0,52/Watt divulgado pela [DME Energética](http://www.dme-pc.com.br/atendimento/tarifas), chegamos ao custo de energia de R$ 312,00/sprint.

- Internet

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

De acordo com o [detalhamento da Release 1 no backlog](./backlog.md#Detalhamento-por-Release), a release 1 conta com 125 story points.

### Parâmetros iniciais da release

|BAC|L|PS|SD|PRP_0|
|-|-|-|-|-|
|R$10298|7|5|07/03/2020|125|

### Sprints

|n|AC|PC|PA|SC|PRP|RPC|APC|PPC|PV|EV|CV|SV|CPI|SPI|ETC|EAC|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|1|R$2059,60|26|0|R$2059,60|125|26|0.208|0.2|R$2059,60|R$2141.98|R$82,38|R$82,38|1.04|1.04|R$7842,33|R$9901,93|
|2|R$4119,20|34|26|R$2059,60|151|60|0.397|0.4|R$4119,20|R$4091,92|R$-27,28|R$-27,28|0.993|0.993|R$6249,83|R$10369,02|
|3|R$6178,80|57|-2|R$2059,60|157|130|0.828|0.6|R$6178,80|R$8526,74|R$2347,94|R$2347,94|1.38|1.38|R$1283,52|R$7462,32|
|4|R$8238,40|26|10|R$2059,60|167|156|0.934|0.8|R$8238,40|R$9618,33|R$1379,93|R$1379,93|1.167|1.167|R$582,41|R$8820,81|
|5|R$10298,00|19|8|R$2059,60|175|175|1.0|1.0|R$10298,00|$10298,00|R$00,00|R$00,00|1.0|1.0|R$00,00|R$10298,00|

### Detalhamento das sprints

Abaixo encontra-se o detalhamento de como os números utilizados na tabela acima foram calculados.

Veja mais detalhes sobre as estórias de usuário no [backlog](./backlog.md). Perceba que, para o EVM foi utilizado um offset de 5 sprints, portanto a sprint 1 do EVM corresponde a sprint 6 do backlog.

#### **Sprint 1**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US45 e US42|16|13|-3|13|[issue #2](https://github.com/parlamentaqui/frontend/issues/2)|
|US04|13|5|-8|5|[issue #7](https://github.com/parlamentaqui/frontend/issues/7)|
|US40|5|13|+8|0|[issue #3](https://github.com/parlamentaqui/frontend/issues/3)|
|US46|5|8|+3|8|[issue #8](https://github.com/parlamentaqui/frontend/issues/8)
|TOTAL|39|39|0|26|-|

#### **Sprint 2**

(Diversas histórias novas devido á quebra de histórias em funcionalidades menores.)

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US40|N/A|N/A|0|0|Dívida técnica não entregue([issue #3](https://github.com/parlamentaqui/frontend/issues/3))|
|US06 E US08|8|3|-5|3|[issue #15](https://github.com/parlamentaqui/frontend/issues/15)|
|US41|0|3|3|3|[issue #16](https://github.com/parlamentaqui/frontend/issues/16)|
|US49|0|5|5|5|[issue #6](https://github.com/parlamentaqui/gateway/issues/6)|
|US50|0|8|8|8|[issue #8](https://github.com/parlamentaqui/gateway/issues/8)|
|US51|0|5|5|5|[issue #7](https://github.com/parlamentaqui/gateway/issues/7)|
|US52|0|5|5|5|[issue #5](https://github.com/parlamentaqui/gateway/issues/5)|
|US53|0|5|5|5|[issue #4](https://github.com/parlamentaqui/gateway/issues/4)|
|total|8|32|26|34|-|

#### **Sprint 3**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US40|N/A|N/A|0|13|Dívida técnica entregue([issue #3](https://github.com/parlamentaqui/frontend/issues/3))|
|US01|8|5|-3|5|[frontend #21](https://github.com/parlamentaqui/frontend/issues/21)|
|US02|8|5|-3|5|[frontend #22](https://github.com/parlamentaqui/frontend/issues/22)|
|US03|8|5|-3|5|[frontend #23](https://github.com/parlamentaqui/frontend/issues/23)|
|US06|3|3|0|3|[frontend #15](https://github.com/parlamentaqui/frontend/issues/15)|
|US09|8|5|-3|5|[frontend #24](https://github.com/parlamentaqui/frontend/issues/24)|
|US37|8|8|0|8|[gateway #11](https://github.com/parlamentaqui/gateway/issues/11)|
|US38|8|13|5|13|[gateway #12](https://github.com/parlamentaqui/gateway/issues/12)|
|US39|8|13|5|13|[gateway #13](https://github.com/parlamentaqui/gateway/issues/13)|
|TOTAL|59|57|-2|70|-|

#### **Sprint 4**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US05|2|2|0|2|[frontend #28](https://github.com/parlamentaqui/frontend/issues/28)|
|US11|3|3|0|3|[frontend #29](https://github.com/parlamentaqui/frontend/issues/29)|
|US15|3|5|2|5|[frontend #31](https://github.com/parlamentaqui/frontend/issues/31)|
|US34|8|8|0|8|[frontend #34](https://github.com/parlamentaqui/frontend/issues/34)|
|US55|0|8|8|8|[frontend #41](https://github.com/parlamentaqui/frontend/issues/41)|
|TOTAL|16|26|10|26|-|

#### **Sprint 5**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US12|3|3|0|3|[frontend #30](https://github.com/parlamentaqui/frontend/issues/30)|
|US16|3|3|0|3|[frontend #32](https://github.com/parlamentaqui/frontend/issues/32)|
|US31|5|13|8|13|[frontend #33](https://github.com/parlamentaqui/frontend/issues/33)|
|TOTAL|11|19|8|19|-|


## Incremento 1

O Incremento 1, composta pela onda 3 do [lean inception](./lean_inception.md) e com as estórias descritas no [detalhamento da Release 2 no backlog](./backlog.md#Detalhamento-por-Release), contem os seguintes parâmetros: 

### BAC - Budget at Complete

Para o calculo do BAC foi levado em conta 3 fatores, descritos abaixo:

**1. Preço da mão de obra de cada aluno da UnB envolvido no projeto**

Para realizar esse calculo, foi utilizado o valor médio de custo por aluno de 15 mil reais/ano, conforme publicado em [matéria do correio braziliense](https://www.correiobraziliense.com.br/app/noticia/eu-estudante/ensino_ensinosuperior/2015/03/05/ensino_ensinosuperior_interna,474102/portas-abertas-ao-cidadao). A matéria não cita fontes porém não foram encontrados outros locais com a informação.

Considerando que o ano possui 2 semestres letivos, e considerando uma média de 360 horas/aula realizada por aluno a cada semestre, chegamos ao valor aproximado de 20 reais/hora.

Considerando o tempo de dedicação de 10 horas/sprint ao projeto, temos um custo por membro de 200 reais por sprint, totalizando 2000 reais/sprint para todo o time.

Levando em conta as 4 sprints com histórias de usuário estimadas, chegamos ao valor de 8000 reais de mão de obra para a release 1.

**2. Custos de serviços de energia e internet**

- Energia

Considerando o consumo de 60 Watts/hora por notebook e levando em conta as mesmas 10 horas de desenvolvimento/sprint, chegamos ao valor de 600 Watts/sprint por membro, totalizando 6000 Watts/sprint para toda a equipe.
Considerando o valor de R$0,52/Watt divulgado pela [DME Energética](http://www.dme-pc.com.br/atendimento/tarifas), chegamos ao custo de energia de R$ 312,00/sprint.

- Internet

Para o custo de serviço de internet, será considerado o valor de R$100/mes para cada membro, totalizando uma média de R$250/sprint para todos os membros do projeto.

**Custo total de serviços de energia e internet**

Com esses valores definidos, chegamos ao valor de R$562,00/sprint, totalizando um custo total de R$2248,00 para o incremento 1.

**Custo total da release**

Somando todos os critérios estabelecidos acima, chegamos ao Budget at Complete de **R$10248,00**.

### L - Sprint Length

A duração da sprint definida para todo o produto foi de 7 dias.

### PS - Planned Sprints

Para o incremento 1 foram planejadas 4 sprints com pontos no total, o detalhamento pode ser visto no [cronograma do produto](./cronograma_do_produto.md)

### SD - Starting Date

A data de inicio do incremento 01 foi definida como dia 11/04/2020.

### PRP - Planned Release Points

De acordo com o [detalhamento do incremento 1 no backlog](./backlog.md#Detalhamento-por-Release), a release 1 conta com 62 story points.

### Parâmetros iniciais da release

|BAC|L|PS|SD|PRP_0|
|-|-|-|-|-|
|R$10248|7|4|11/04/2020|62|

### Sprints

|n|AC|PC|PA|SC|PRP|RPC|APC|PPC|PV|EV|CV|SV|CPI|SPI|ETC|EAC|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|1|R$2562,00|15|-3|R$2562,00|59|15|0.242|0.25|R$2562,00|R$2480,02|-R$81,98|-R$81,98|0.968|0.968|R$8024,77|R$10586,77|
|2|R$5124,00|0|10|R$2562,00|69|15|0.217|0.5|R$5124,00|R$2223,82|-R$2900,18|-R$2900,18|0.434|0.434|R$18488,89|R$23612,89|
|3|R$7686,00|18|0|R$2562,00|69|33|0.478|0.75|R$7686,00|R$4898,54|-R$2787,46|-R$2787,46|0.637|0.637|R$8397,90|R$16083,90|
|4|R$10248,00|37|1|R$2562,00|70|70|1|1|R$10248,00|R$10248,00|R$00,00|R$00,00|1.0|1.0|R$0,00|R$10248,00|

### Detalhamento das sprints

Abaixo encontra-se o detalhamento de como os números utilizados na tabela acima foram calculados.

Veja mais detalhes sobre as estórias de usuário no [backlog](./backlog.md). Perceba que, para o EVM foi utilizado um offset de 5 sprints, portanto a sprint 6 do EVM corresponde a sprint 11 do backlog.

#### **Sprint 6**

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US33|5|5|0|5|https://github.com/parlamentaqui/frontend/issues/45|
|US54|5|5|0|5|https://github.com/parlamentaqui/gateway/issues/21|
|US56|8|5|-3|5|https://github.com/parlamentaqui/frontend/issues/46|
|TOTAL|18|15|-3|15|-|

#### **Sprint 7**


|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US07|8|13|5|0|https://github.com/parlamentaqui/frontend/issues/61|
|US10|5|5|0|0|https://github.com/parlamentaqui/frontend/issues/59|
|US19|8|13|5|0|https://github.com/parlamentaqui/frontend/issues/60|
|total|21|31|10|0|-|

#### **Sprint 8**

Sprint dedicada á resolução de dívidas técnicas.

|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US10|-|-|-|5|Dívida técnica entregue(https://github.com/parlamentaqui/frontend/issues/59)|
|US19|-|-|-|13|Dívida técnica entregue(https://github.com/parlamentaqui/frontend/issues/60)|
|TOTAL|0|0|0|18|-|


#### **Sprint 9**


|US|Pontos estimados|Pontuação Final|Variação (PA)|Pontuação entregue|Rastreamento|
|-|-|-|-|-|-|
|US07|-|-|-|13|Dívida técnica entregue(https://github.com/parlamentaqui/frontend/issues/61)|
|US17|2|3|1|3|https://github.com/parlamentaqui/frontend/issues/71|
|US20|8|8|0|8|https://github.com/parlamentaqui/frontend/issues/72|
|US21|13|13|0|13|https://github.com/parlamentaqui/frontend/issues/73|
|TOTAL|23|24|1|37|-|

