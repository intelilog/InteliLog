# Aprendizado por Projeto Integrador (API)

Projeto baseado na Metodologia SCRUM para acompanhamento do desempenho de municípios do estado de São Paulo.

# Índice
* [Projeto](#projeto)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Backlog do Produto](#backlog-do-produto)

# Projeto
Acompanhamento dos Resultados de Exportação dos Municípios do Estado de São Paulo, baseando-se nos dados abertos do Ministério do Desenvolvimento, Indústria, Comércio e Serviços.


# Equipe
| Função | Nome | LinkedIn & GitHub |
| :---   |:--- |       :---       |
| Product Owner   | Natalia Costa   |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/natalia-costa-469a662b1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/natcsantos)              |    
| Scrum Master   | Amanda Izumi   |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amanda-izumi-analistaadmfinanceiro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/AmandaIzumi23)     |
| Team Member   | Luany Moreira           |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luany-moreira-de-paula-a25a78343?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/Nepoun)        |
|  Team Member  | Manoela Nobre             |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/manoela-batista-nobre-800206271?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/CaioVitorDias1)        |
|  Team Member  | Guilherme Braga              |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-braga-873592356?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/braga2601)   |
|  Team Member  | Vinicius Felix   |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/vin%C3%ADcius-felix-teixeira-0692a2357?trk=contact-info) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/gioliveirass)          |
|  Team Member  | Nykollas Martins    |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/nykollas-martins-b220302b0?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=GitHub&logoColor=white)](https://GitHub.com/Nykollas27)          |


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
 > * Slack
  
 ### Tecnologias da Informação
 > * Power B.I  
 > * Python 3+

# Backlog do produto

## Sprint 1
- [x] Dar acesso do Jira Software a todos do grupo;
- [x] Criar BackLog;
- [x] Alinhamento do Grupo quanto aos requisitos do cliente;
- [x] Baixar bases públicas no site ComexStat;
- [x] Salvar as bases no GitHub em duas versões (Completa e Compilada);
- [x] Tratar bases em Python (Compilar e transformar dados);
- [x] Criar um dashboard piloto em  Excel com a base compilada;
- [x] Validação e apresentação da proposta do dashboard piloto ao cliente;
- [x] Salvar arquivo da proposta piloto no GitHub do grupo.

## User Story
Rank | Prioridade | User Story | Estimativa de Tempo | Sprint | Requisitos do Parceiro |
|------|--------|---------------------|--------|----------|---------|
| 1 | Alta | Como cliente quero identificar quais países tem aumentado a importação de produtos específicos dos municípios paulistas para explorar novos mercados. | Uma semana | 1 | 2 |
| 2 | Alta | Como cliente quero saber se os municípios concentraram suas exportações em poucos produtos ou apresentaram uma pauta diversificada para avaliar a necessidade de diversificação.  | Uma semana | 1 | 4 |
| 1 | Alta | Como cliente quero compreender com base na tendência histórica, quais são as projeçõs para o desempenho comercial dos municípios nos próximos anos para planejar meu futuro. | Uma semana | 1 | 10 |

### MVP - Sprint 1
![Image](https://github.com/user-attachments/assets/a5053abb-4c0d-46a9-b142-f024938cdbe0)

## Sprint 2
- [x] Iniciar o Dashboard em PowerBI, carregando e transformando as bases;
- [x] Iniciar os relacionamentos necessários no Dashboard no PowerBI;
- [x] Criação das medidas;
- [x] Iniciar a parte da visualização das principais métricas solicitadas;
- [x] Testar o Dashboard;
- [x] Formatar o Dashboard conforme requisitos do cliente;
- [x] Salvar o Dashboard em PowerBI no GitHub.

## User Story
Rank | Prioridade | User Story | Estimativa de Tempo | Sprint | Requisitos do Parceiro |
|------|--------|---------------------|--------|----------|---------|
| 4 | Média | Como cliente, quero comparar o desempenho comercial do meu município com outros municípios vizinhos ou de porte semelhante, para identificar oportunidades de melhoria. | Duas semanas | 2 | 1 |
| 5 | Média | Como cliente quero analisar como mudanças em políticas tarifárias ou acordo comerciais afetaram as exportações e importações para adaptar minhas estratégias. | Duas semanas | 2 | 3 |
| 6 | Média | Como cliente quero identificar quais são as principais vias de transporte utilizada para escoar exportações e receber importações e como isso afeta os custos e a eficiência logística para otimizar custos e eficiência logística. | Duas semanas | 2 | 5 |
| 9 | Média | Como cliente quero entender quem são os principais fornecedores e clientes internacionais das empresas nos municípios, para entender como essas relações imapactam a economia local. | Duas semanas | 2 | 8 |  

### MVP - Sprint 2
![Image](https://github.com/user-attachments/assets/3a63b4cd-a96d-45af-ac48-6522f05c6762)


## Sprint 3
- [x] Finalização da formatação do PowerBI;
- [x] Ajustes conforme solicitação do cliente.

## User Story
Rank | Prioridade | User Story | Estimativa de Tempo | Sprint | Requisitos do Parceiro |
|------|--------|---------------------|--------|----------|---------|
| 7 | Baixa | Como cliente quero entender padrões sazonais nas exportações/importações de determinados produtos e entender como as empresas locais lidam com essas variações para planejar minha produção e estoque. | Três semanas | 3 | 6 |
| 8 | Baixa | Como cliente quero visualizar como os produtos exportados se posicionam em termos de preço e qualidade nos mercados internacionais para melhorar minha competitividade. | Três semanas | 3 | 7 |
| 10 | Baixa | Como cliente quero acessar quais os riscos associados à dependência de mercados específicos ou de poucos parceiros comerciais para mitigar estes riscos. | Três semanas | 3 | 9 |

### MVP - Sprint 3
![Image](https://github.com/user-attachments/assets/8d6ef2f1-3d17-4c5d-b5cb-31ccebed642d)

      
## Sprint 4
- [x] Apresentação do resultado final.

# Registro das Sprints

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
| Sprint 01 | 07/04/2025 | Finalizada | [MVP](https://github.com/intelilog/InteliLog/raw/refs/heads/main/API%201%20-%20Sprint%201.xlsx) | 
| Sprint 02 | 05/05/2025 | Finalizada |[MVP](https://github.com/intelilog/InteliLog/raw/refs/heads/main/Sprint2.pbix) | 
| Sprint 03 | 26/05/2025 | Finalizada |[MVP](https://github.com/intelilog/InteliLog/raw/refs/heads/main/Sprint3.pbix) | 
| Feira de Soluções | 17/06/2025 | A realizar | [MVP](https://)
