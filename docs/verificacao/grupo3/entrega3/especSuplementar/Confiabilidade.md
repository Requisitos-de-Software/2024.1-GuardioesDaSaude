# Verificação Especificação Suplementar – Confiabilidade


## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Lista de Verificação](#Lista-de-Verificação)
* [Avaliação](#Avaliação)
* [Conclusão e Observações](#Conclusão-e-Observações)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

Este documento apresenta uma lista de verificação para a avaliação do tópico de confiabilidade na especificação suplementar do projeto dos Correios. Dessa maneira, através da lista de verificação, será buscado identificar de forma objetiva e detalhada os requisitos relacionados à confiabilidade presentes na especificação suplementar ao garantir que eles estejam alinhados com as necessidades e com as expectativas dos usuários finais.

## Metodologia 

Para conduzir a avaliação dos requisitos de confiabilidade, inicialmente, será elaborado uma lista de verificações com base em materiais didáticos sobre a especificação suplementar. Em seguida, um integrante do grupo irá revisar essa especificação com base nesta lista.


## Lista de Verificação

A tabela 1 apresenta a lista de verificação para a especificação suplementar em relação ao tópico de confiabilidade.

<center>

**Tabela 1:** Lista de verificação para a confiabilidade na especificação suplementar.


| ID  | Pergunta  | Observação   | Rastreabilidade  |
|-----|-----|-----|-----|
| 1  | O documento define claramente os requisitos de confiabilidade para o sistema? | Deve haver uma definição clara e detalhada dos requisitos de confiabilidade esperados para o sistema, incluindo métricas específicas. | "Software Reliability Engineering," John Musa, Capítulo 2, tópico "Defining Reliability Requirements" |
| 2  | O documento especifica as metas de tempo médio entre falhas (MTBF) e tempo médio para reparo (MTTR)? | Deve incluir metas específicas para MTBF e MTTR, que são métricas comuns de confiabilidade. | "Handbook of Software Reliability Engineering," Michael R. Lyu, Capítulo 4, tópico "Reliability Metrics" |
| 3  | O documento descreve os procedimentos de teste para verificar a confiabilidade? | Deve detalhar os procedimentos de teste utilizados para assegurar que os requisitos de confiabilidade são atendidos. | "Practical Guide to Software System Testing," Ilene Burnstein, Capítulo 8, tópico "Reliability Testing" |
| 4  | O documento identifica os cenários de falha esperados e suas respectivas soluções de mitigação? | Deve listar os cenários de falha previstos e as estratégias para mitigar ou resolver essas falhas. | "Software Reliability: Measurement, Prediction, Application," John D. Musa, Capítulo 5, tópico "Failure Management" |
| 5  | O documento inclui uma análise de impacto de falhas críticas? | Deve incluir uma análise detalhada do impacto que falhas críticas poderiam ter no sistema e nas operações dos usuários. | "Reliability Engineering," Elsayed A. Elsayed, Capítulo 6, tópico "Impact Analysis" |
| 6  | O documento especifica os requisitos de disponibilidade do sistema? | Deve haver uma especificação clara sobre os requisitos de disponibilidade, incluindo porcentagens ou tempos de operação esperados. | "Dependability Metrics," I. Koren, C. M. Krishna, Capítulo 3, tópico "System Availability" |
| 7  | O documento aborda a redundância e recuperação de falhas? | Deve descrever as técnicas de redundância e os procedimentos de recuperação de falhas implementados no sistema. | "Fault-Tolerant Systems," Israel Koren, C. Mani Krishna, Capítulo 7, tópico "Redundancy and Recovery" |
| 8  | O documento inclui requisitos de manutenção preventiva? | Deve especificar os requisitos e os planos para a manutenção preventiva do sistema para garantir a confiabilidade contínua. | "Maintenance and Reliability Best Practices," Ramesh Gulati, Capítulo 9, tópico "Preventive Maintenance" |
| 9  | O documento descreve os procedimentos para atualizações e patches de software? | Deve detalhar os procedimentos para a implementação de atualizações e patches de software para manter a confiabilidade do sistema. | "Software Maintenance: Concepts and Practice," Penny Grubb, Armstrong A. Takang, Capítulo 10, tópico "Software Updates" |
| 10  | O documento define como a confiabilidade será monitorada e reportada após a implementação? | Deve descrever os métodos e ferramentas que serão usados para monitorar e relatar a confiabilidade do sistema em operação. | "Reliability and Maintainability in Perspective," David J. Smith, Capítulo 8, tópico "Reliability Monitoring" |


**Autor:** [Luana Medeiros](https://github.com/LuaMedeiros)

</center>


## Avaliação

A tabela 2 apresenta a avaliação da especificação suplementar em relação ao tópico de confiabilidade.

<center>

**Tabela 2:** Avaliação da confiabilidade na especificação suplementar.

| ID  | Pergunta  | Resposta   | Observação  |
|-----|-----|-----|-----|
| 1  | O documento define claramente os requisitos de confiabilidade para o sistema? | Sim |  |
| 2  | O documento especifica as metas de tempo médio entre falhas (MTBF) e tempo médio para reparo (MTTR)? | Não | Não tem especificado MTBF nem MTTR |
| 3  | O documento descreve os procedimentos de teste para verificar a confiabilidade? | Não | Não possui detalhamento do procedimento de teste para verificar a confiabilidade |
| 4  | O documento identifica os cenários de falha esperados e suas respectivas soluções de mitigação? | Não | Não contém os cenários de falha esperados e suas respectivas soluções de mitigação |
| 5  | O documento inclui uma análise de impacto de falhas críticas? | Não | Não foi realizado uma análise de impacto de falhas críticas |
| 6  | O documento especifica os requisitos de disponibilidade do sistema? | Sim |  |
| 7  | O documento aborda a redundância e recuperação de falhas? | Não | Não possui redundância e recuperação de falhas |
| 8  | O documento inclui requisitos de manutenção preventiva? | Não | Não foi incluido requisitos de manutenção preventiva |
| 9  | O documento descreve os procedimentos para atualizações e patches de software? | Não | Os procedimentos para atualizações e patches de software não são descritos |
| 10  | O documento define como a confiabilidade será monitorada e reportada após a implementação? | Não | Não é definido como a confiabilidade será monitorada e reportada após a implementação |

**Autor:** [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

## Conclusão e Observações

A avaliação do documento de Especificação Suplementar de Confiabilidade mostra que ele define claramente os requisitos de confiabilidade e especifica a disponibilidade do sistema, mas apresenta falhas significativas. Ele não inclui metas de tempo médio entre falhas (MTBF) e tempo médio para reparo (MTTR), procedimentos de teste, cenários de falha esperados, análise de impacto de falhas críticas, ou estratégias de redundância e recuperação. Além disso, faltam requisitos de manutenção preventiva, procedimentos para atualizações de software, e diretrizes para monitoramento e relatório de confiabilidade. Recomenda-se uma revisão abrangente para incluir esses elementos cruciais.

## Bibliografia

1. MUSA, J. Software reliability engineering: More reliable software faster and cheaper 2nd edition. 2. ed. Bloomington, MN, USA: AuthorHouse, 2004.

2. SHAHABUDDIN, P. Reliability engineering, 1996, by elsayed A. elsayed (reading, mass.: Addison Wesley longman, inc.), 737 pp. ISBN 0-201-63481-3. Probability in the engineering and informational sciences, v. 12, n. 4, p. 533–534, 1998.


## Histórico de versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação do documento | Luana Medeiros | - | 10/06/2024 |
