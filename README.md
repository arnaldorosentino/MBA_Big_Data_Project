# MBA_Big_Data_Project

## Objetivo
Explorar o Dataset “Atendimento a pedidos de conexões MMGD - Mini e Microgeração distribuída - pós Lei 14300” disponibilizado pela Agência Nacional de Energia Elétrica (ANEEL).
Trata-se de dados solicitados por meio do OFÍCIO CIRCULAR nº 5/2023- SFE/SRD/SMA/ANEEL (Documento SICnet ANEEL nº 48534.000626/2023-00) com o objetivo de obter informações para promover o acompanhamento dos atendimentos realizados pelas Distribuidoras às solicitações de conexão de unidades com microgeração ou minigeração distribuída, realizadas no período entre 7 de janeiro de 2022 e 7 de janeiro de 2023, com finalidade de participação no Sistema de Compensação de Energia Elétrica (SCEE), nos termos da Lei nº 14.300, de 6 de janeiro de 2022.

## Problema de Negócio
A análise pode explorar as ineficiências no processo de atendimento das solicitações de conexão, tais como rejeições e a distribuição desigual de solicitações atendidas entre diferentes distribuidoras, estados, municípios e tipos de grupo tarifário. Identificar esses problemas pode melhorar a eficiência operacional e a satisfação dos consumidores, além de promover a geração de energia renovável no país.

## Dados Disponíveis para Análise

* [Link de Acesso](https://dadosabertos.aneel.gov.br/dataset/atendimento-mmgd-mini-e-micro-geracao-distribuida)

**Descrição das Variáveis:**

*	Sigla da Distribuidora de Energia
*	Nome da Unidade da Federação (Estado e Distrito Federal) Nome do Município onde atribuído pelo IBGE em que se situa o empreendimento.
*	Data de Solicitação
*	Tipo de Geração:
> -  UTN - Usina Termonuclear
> -  UTE - Usina Termelétrica
> -  UHE - Usina Hidrelétrica
> -  UFV - Central Geradora Solar Fotovoltaica
> -  PCH - Pequena Central Hidrelétrica
> -  EOL - Central Geradora Eólica
> -  CGU - Central Geradora Undi-elétrica
> -  CGH - Central Geradora Hidrelétrica
*	Modalidade de Geração: 
> -  Geração Compartilhada
> -  Geração Local
> -  Autoconsumo Remoto
> -  EMUCs
*	Status Conexão:
> -  Pedido em estoque
> -  Pedido conectado
> -  Pedido negado
*	Subgrupo Tarifário:
> -  A1 - tensão de fornecimento igual ou superior a 230 kV
> -  A2 - tensão de fornecimento de 88 kV a 138 kV
> -  A3 - tensão de fornecimento de 69 kV
> -  A3a - tensão de fornecimento de 30 kV a 44 kV
> -  A4 - tensão de fornecimento de 2,3 kV a 25 kV
> -  A5 – subterrâneo
> -  B1 – residencial
> -  B2 – rural
> -  B3 - demais classes
> -  B4 - iluminação pública
*	Potência da central de microgeração ou minigeração

*Obs.: Há outros dados, porém, grande parte não possui informações adequadas e, portanto, serão excluídas da análise.*

## Hipóteses a Validar
1. **Hipótese 1:** Existem discrepâncias significativas entre diferentes distribuidoras no que tange à eficiência do atendimento às solicitações.
2. **Hipótese 2:** Alguns estados têm uma proporção maior de solicitações negadas.
3. **Hipótese 3:** Solicitações de conexão para certos tipos de modalidades são mais propensas a serem negadas.
4. **Hipótese 4:** O subgrupo tarifário ao qual o consumidor pertence influencia o status da conexão.
5. **Hipótese 5:** A potência da central de microgeração ou minigeração está correlacionada com o status da conexão.

## Conclusões Possíveis
1. **Análise de Distribuidoras:** Identificar as distribuidoras que têm melhor desempenho e as que necessitam melhorar seus processos de atendimento a solicitações.
2. **Análise Regional:** Detectar regiões ou localidades com alta incidência de problemas, possibilitando investigar causas subjacentes, como legislação local e infraestrutura. A análise regional permite identificar ainda as regiões com maior potência instalada no período sob análise.
3. **Análise de Tipo de Geração e Modalidade:** Verificar se certos tipos de modalidades são mais desafiadores e requerem aprimoramento em procedimentos ou políticas específicas.
4. **Análise de Subgrupo Tarifário:** Avaliar se os consumidores de determinados subgrupos enfrentam mais barreiras, necessitando de intervenções regulatórias ou incentivos.
5. **Análise de Potência:** Investigar a influência da potência na conexão.
