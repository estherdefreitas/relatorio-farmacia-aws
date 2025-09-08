# Termo de Acordo de Nível de Serviço (SLA)

**Empresa Contratante:** Abstergo Industries

**Fornecedora de Serviços Cloud:** Esther Nascimento Soares de Freitas

**Data de Início:** 08/09/2025

**Data de Vigência:** 12 meses, renováveis automaticamente salvo manifestação contrária.

---

## 1. Objetivo

Este Termo de Acordo de Nível de Serviço (SLA) tem como objetivo definir os compromissos, responsabilidades e métricas de desempenho referentes à implementação e manutenção dos serviços AWS contratados pela Abstergo Industries.

## 2. Serviços Abrangidos

Os seguintes serviços da AWS fazem parte deste acordo:

- Amazon S3 (Simple Storage Service) – Armazenamento de documentos, históricos de pedidos e backups.
- Amazon RDS (Relational Database Service) – Banco de dados relacional para controle de estoques, fornecedores e pedidos.
- Amazon EC2 (Elastic Compute Cloud) com Auto Scaling – Hospedagem de sistemas internos e de integração com parceiros.

## 3. Indicadores de Nível de Serviço
### 3.1 Disponibilidade

- Amazon S3: 99,9% de disponibilidade mensal.
- Amazon RDS: 99,95% de disponibilidade mensal em instância Multi-AZ.
- Amazon EC2 + Auto Scaling: 99,9% de disponibilidade mensal.

Caso os serviços apresentem indisponibilidade superior a 0,1% do tempo mensal, serão aplicados créditos financeiros conforme política de SLA da própria AWS.

### 3.2 Tempo de Resposta (Consultoria)

- Atendimento a incidentes críticos (serviço inoperante): até 2 horas.
- Atendimento a incidentes não críticos (lentidão, falha parcial): até 6 horas úteis.
- Atendimento a solicitações de melhorias: até 5 dias úteis.

### 3.3 Segurança e Backup

- Backups automáticos diários no Amazon RDS.
- Versionamento de arquivos ativado no Amazon S3.
- Políticas de acesso configuradas com princípio de privilégio mínimo.
- A responsabilidade pelo gerenciamento de senhas e acessos dos usuários finais é da Abstergo Industries.

## 4. Responsabilidades
### 4.1 Responsabilidades da Consultoria

- Implementar, configurar e manter os serviços AWS listados.
- Monitorar métricas de disponibilidade e desempenho.
- Reportar mensalmente à Abstergo um resumo de consumo e custos.
- Apoiar a Abstergo em auditorias de segurança e conformidade.

### 4.2 Responsabilidades da Abstergo Industries

- Informar previamente demandas de expansão ou novos serviços.
- Garantir a conformidade legal no uso dos dados armazenados.
- Manter controle interno sobre credenciais e usuários finais.
- Efetuar pagamentos mensais dentro do prazo acordado.

## 5. Penalidades

Caso a Consultoria Cloud Solutions não cumpra os tempos de resposta acordados, será concedido crédito de 5% de desconto na fatura de serviços de consultoria por cada ocorrência.

Em caso de falha de disponibilidade acima do limite contratado, aplicam-se créditos conforme política oficial da AWS.

## 6. Vigência e Revisão

Este SLA entra em vigor em 08/09/2025, com prazo inicial de 12 meses.

O documento poderá ser revisado anualmente ou mediante solicitação de qualquer parte.
