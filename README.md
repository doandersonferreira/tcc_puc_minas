# Trabalho de Conclusão de Curso PUC MINAS

Repositório destinado a armazenar os arquivos de dados e os scripts .ipynb utilizados no TCC.

**Tema do TCC**: ESTUDO SOBRE OCORRÊNCIAS AERONÁUTICAS NA AVIAÇÃO CIVIL BRASILEIRA E APLICAÇÃO DE MODELOS DE MACHINE LEARNING PARA CLASSIFICAÇÃO DOS TIPOS DE OCORRÊNCIA

**Datasets baixados em**: 28/12/2021

**Cobertura temporal do conjunto de dados**: 03/01/2010 a 18/08/2021

**Fonte dos Dados**: https://dados.gov.br/dataset/ocorrencias-aeronauticas-da-aviacao-civil-brasileira

## Contextualização

Em novembro do ano de 2021, o Brasil chorou e lamentou a perda de uma das maiores e mais poderosas vozes sertanejas da atualidade em um acidente aéreo. A partir de eventos como esse e a massiva divulgação de casos semelhantes por parte da mídia, somos instigados a buscar mais informações sobre acidentes aéreos no Brasil.

Em [matéria do Jornal O Globo](https://valor.globo.com/empresas/noticia/2016/05/09/anac-sobe-de-21a-a-5a-em-ranking-mundial-de-seguranca-na-aviacao.ghtml), de 09/05/2016, a ANAC (Agência Nacional de Aviação Civil) havia sido promovida do 21º posição (reconhecida em 2009) para a 5ª colocação no Ranking Mundial de segurança na aviação.  Na ocasião, a Organização de Aviação Civil Internacional deu ao Brasil o percentual de 95,07% de conformidade no Universal Safety Oversight Audit Programme - Continuous Monitoring Approach (USOAP CMA), programa lançado em resposta às preocupações sobre a adequação da vigilância da segurança operacional da aviação civil em todo o mundo.

E com o aumento dos protocolos de segurança e o avanço das tecnologias na área da aviação civil brasileira, será que há redução do número de acidentes registrados no decorrer dos anos? 

Motivado pela curiosidade, realizei pesquisas sobre dados públicos de acidentes aéreos e encontrei um órgão do Comando da Aeronáutica chamado Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA), que é responsável por investigar acidentes aeronáuticos da aviação civil e da Força Aérea Brasileira. É com base nos dados disponibilizados por esse órgão que se pretende realizar o estudo sobre as ocorrências aeronáuticas na aviação civil brasileira.

## O problema proposto

Para auxiliar no entendimento do problema proposto, utilizamos a técnica dos 5 W’s, ou seja, perguntas cujas respostas são consideradas básicas na coleta de informações ou solução de problemas.

- **Por que? (Why?)**: Procura-se entender o panorama atual de ocorrências aeronáuticas da aviação civil brasileira. 
- **Quem? (Who?)**: O presente projeto tem como objetivo trabalhar sobre os dados abertos de ocorrências de acidentes ou incidentes aéreos gerenciados pelo Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA). 
- **O que? (What?)**: Utilizaremos a análise exploratória sobre os dados com objetivos de extrair informações de valor e utilizar ao menos três algoritmos de predição (Machine Learning) para classificar tipos de ocorrência baseado nas características, selecionar o modelo de classificação mais eficiente e aplicar previsões em conjunto de dados de validação. 
- **Onde? (Where?)**: Trataremos somente de ocorrências aeronáuticas registradas dentro do território brasileiro.
- **Quando? (When?)**: O período analisado contém registros de ocorrências entre 01/2010 a 08/2021.


## Datasets utilizados:

1.	OCORRENCIA.csv - Informações sobre as ocorrências aeronauticas. 
2.	OCORRENCIA_TIPO.csv - Informações sobre o tipo de ocorrências aeronauticas.
3.	AERONAVE.csv - Informações sobre as aeronaves envolvidas nas ocorrências.
