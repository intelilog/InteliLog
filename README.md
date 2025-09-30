# Aprendizado por Projeto Integrador (API)

Projeto baseado na Metodologia SCRUM para acompanhamento do fluxo de cargas especiais e perigosas de empresas com registro no RAPP e análise estatística de acidentes viários com veículos pesados e avaliação de proximidade dos acidentes com pontos de parada de descanso.

# Índice
* [Projeto](#projeto)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Backlog do Produto](#backlog-do-produto)

# Projeto
Fluxo de Cargas Especiais e Perigosas e análise estatística de acidentes por veículos pesados e acidentes próximos aos pontos de descansos.


# Equipe
| Função | Nome | LinkedIn & GitHub |
| :---   |:--- |       :---       |
| Product Owner   | Natalia Costa   |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/natalia-costa-469a662b1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/natcsantos)              |    
| Scrum Master   | Amanda Izumi   |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amanda-izumi-analistaadmfinanceiro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/AmandaIzumi23)     |
| Team Member   | Luany Moreira           |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luany-moreira-de-paula-a25a78343?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/Nepoun)        |
|  Team Member  | Rafaela da Motta             |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rafaela-da-motta-ribeiro-442015340/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/Rafamottar/LOG_INF)        |
|  Team Member  | Guilherme Braga              |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-braga-873592356?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/braga2601)   |
|  Team Member  | Vinicius Felix   |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/vin%C3%ADcius-felix-teixeira-0692a2357?trk=contact-info) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/gioliveirass)          |
|  Team Member  | Maria Heloiza Machado    |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/maria-heloiza-dos-santos-machado-7884422b7) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/Helo219)          |


# Objetivo do Projeto
Este projeto tem como objetivo desenvolver uma plataforma em BI, que:
* Permite visualizar informações sobre o desempenho dos municípios dos estados de SP com base nos dados abertos;
* Fornece dados claros e acessíveis para identificação de municípios que estejam em ascensão, estagnação ou declínio no mercado internacional;
* Segmenta os municípios, apresentando as principais cargas movimentadas, ranking por valor agregado de exportação e importação e a evolução histórica da balança comercial;
* Permite buscar cargas por código NCM;
* Possuí uma visualização gráfica interativa que apresenta a evolução da balança comercial dos municípios de 2023 a 2024.

## Tecnologias Utilizadas

 ### Tecnologias Específicas/Apoio
 > * GitHub
 > * Jira Software
  
 ### Tecnologias da Informação
 > * Power B.I  
 > * Python 3+

# Backlog do produto

## Sprint 1
- [x] Criar visualização interativa com drill-down. Permitir filtros de ano/estado;
- [x] Levantar todas as fontes de dados (bases abertas, APIs, arquivos CSV/Excel), Valida-las e compacta-las;
- [x] Criar script ETL para padronização de campos. Implementar regras de limpeza (duplicatas, nulos, inconsistências);
- [x] Criar indicadores e graficos de cada modal;
- [x] Desenvolver dashboard com gráfico de barras. Implementar filtros por região, ano e tipo de carga;
- [x] Visual e auxiliar nas analises gráficas;
- [x] Slides de apresentação;
- [x] Alinhar Github da Empresa;
- [x] Classificar cargas por volume movimentado.

## User Story
Rank | Prioridade | User Story | Estimativa (Semanas) | Sprint | Requisitos do Parceiro |
|------|--------|---------------------|--------|----------|---------|
| 1 | Alta | Como tomador de Decisões de políticas públicas, solicito a limpeza e o tratamento dos dados das bases públicas sobre cargas perigosas, a fim de iniciar análises confiáveis. | 1 | 1 | 1 |
| 2 | Alta | Como tomador de Decisões de políticas públicas, gostaria de compreender de forma clara quais são os principais modais de tranpsorte utilizados na movimentação de cargas perigosas.  | 1 | 1 | 1 |
| 3 | Alta | Como tomador de Decisões de políticas públicas, desejo vizualizar de forma interativa as principais cargas perigosas movimentadas, para apoiar a formulação de políticas de segurança.  | 1 | 1 | 1 |



## Sprint 2
- [] Média de volume movimentado por empresa;
- [] Criar ranking top 20 empresas. Desenvolver dashboard com filtros por estado;
- [] Contar movimentações por par origem-destino;
- [] Implementar filtros interativos;
- [] Testar o Dashboard;
- [] Agregar dados por mês/ano. Criar série temporal;

## User Story
Rank | Prioridade | User Story | Estimativa (Semanas) | Sprint | Requisitos do Parceiro |
|------|--------|---------------------|--------|----------|---------|
| 4 | Média | Como tomador de Decisões de políticas públicas, quero identificar uma análise estatística de acidentes viários. | 2 | 2 | 1 |
| 5 | Alta | Como tomador de Decisões de plíticas públicas, quero vizualizar as principais empresas responsáveis pela movimentação de cargas perigosas declaradas, a fim de compreender a estrutura do setor e identificar atores críticos na cadeia logística. | 2 | 2 | 3 |
| 6 | Média | Como tomador de Decisões de políticas públicas, quero identificar as principais origens e destinos de cargas perigosas, a fim de mapear fluxos críticos. | 2 | 2 | 5 |
| 7 | Média | Como tomador de Decisões de políticas públicas, quero acompanhar a evolução da movimentação de cargas perigosas ao longo do tempo, para avaliar tendências de crescimento ou redução do setor. | 2 | 2 | 5 |
 
## Sprint 3
- [ ] Classificar municípios em alto/médio/baixo risco;
- [ ] Calcular taxa de acidentes por km;
- [ ] Identificar áreas com baixa cobertura. Gerar relatório de recomendações;
- [ ] Mapear pontos de parada existentes. Calcular distância entre acidentes e paradas

## User Story
Rank | Prioridade | User Story | Estimativa de Tempo | Sprint | Requisitos do Parceiro |
|------|--------|---------------------|--------|----------|---------|
| 8 | Média | Como tomador de Decisões de plíticas públicas, quero identificar as localidades com maior incidência de acidentes envolvendo veículos pesados, para avaliar riscos logísticos. | 3 | 3 | 6 |
| 9 | Baixa | Como tomador de Decisões de plíticas públicas, quero analisar as distâncias entre as localidades com maiores indices de acidentes e os locais de paradas de descanso, para avaliar a relação entre infraestrutura e segurança viária. | 3 | 3 | 7 |



# Registro das Sprints

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
| Sprint 01 | 01/10/2025 | A realizar | [MVP](https://)| 
| Sprint 02 | 00/00/2025 | A realizar |[MVP](https://) | 
| Sprint 03 | 0/00/2025 | A realizar |[MVP](https://) | 
| Feira de Soluções | 04/12/2025 | A realizar | [MVP](https://)
