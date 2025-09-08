# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 08/09/2025

**Empresa:** Abstergo Industries

**Responsável:** Esther Nascimento Soares de Freitas

---


## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por **Esther Nascimento Soares de Freitas**.

O objetivo do projeto é modernizar a infraestrutura, reduzir custos com servidores locais, aumentar a eficiência operacional, e garantir escalabilidade eficiente para integração com parceiros farmacêuticos.O objetivo do projeto foi elencar 3 serviços AWS estratégicos 

Como a Abstergo Industries atua com distribuição farmacêutica, em comunicação com diversas empresas e farmácias, a adoção da nuvem será essencial para reduzir a dependência de infraestrutura física, melhorar a segurança e viabilizar a futura atuação como revendedora digital (B2B). Para isso, foram escolhidos inicialmente 3 serviços AWS estratégicos, com foco em custo-benefício, eficiência operacional e escalabilidade, considerando a ausência de nuvem atualmente e a necessidade de expansão futura.

---

## Descrição do Projeto

O projeto de implementação de serviços AWS foi estruturado em 3 etapas iniciais, cada uma trazendo um ganho específico para o negócio:

### Etapa 1 – Armazenamento em Nuvem - Amazon S3 (Simple Storage Service)

- **Objetivo:** Reduzir custos com armazenamento físico e servidores locais, oferecendo armazenamento em nuvem altamente escalável e seguro. O pagamento é apenas pelo que for utilizado (pay-as-you-go).
- **Principal ganho:** Eliminação de custos com datacenter físico, backups e manutenção de servidores. Maior segurança e disponibilidade dos dados da Abstergo.
- Caso de uso e implementação:
  - Armazenamento centralizado de documentos, contratos, notas fiscais e históricos de pedidos.
  - Backup automático e versionamento, evitando perda de informações críticas.
  - Integração com parceiros farmacêuticos por meio de links de compartilhamento seguros.
 
### Etapa 2 – Banco de Dados - Amazon RDS (Relational Database Service) ou DynamoDB

- **Objetivo:** Otimizar custos e gestão de banco de dados, eliminando a necessidade de administradores dedicados para tarefas repetitivas.
- **Principal ganho:** Redução de custos de manutenção e operação de banco de dados, com escalabilidade automática e alta disponibilidade.
- **Caso de uso e implementação:**
  - Criação de um banco de dados central para controle de estoques, pedidos e fornecedores.
  - Migração gradual de sistemas legados locais para o RDS ou DynamoDB.
  - Garantia de segurança com backups automáticos.
 
### Etapa 3 – Amazon EC2 (Elastic Compute Cloud) + AWS Auto Scaling

- **Objetivo:** Reduzir custos com servidores dedicados e permitir escalabilidade conforme a demanda.
- **Principal ganho:** Flexibilidade para aumentar ou diminuir a capacidade computacional, pagando apenas pelo uso. Redução de custos em períodos de baixa demanda e capacidade extra em períodos críticos (ex.: lançamentos de produtos ou aumento de pedidos).
- **Caso de uso e implementação:**
  - Hospedagem do sistema de gestão logística da Abstergo.
  - Criação de um ambiente escalável para atender tanto operações internas quanto clientes externos.
  - Implementação de políticas de Auto Scaling, ajustando automaticamente os recursos conforme picos de pedidos e acesso ao sistema.
 
---

## Conclusão

A implementação dos serviços AWS na empresa Abstergo Industries tem como esperado:

- Redução de custos com infraestrutura física (energia, refrigeração, espaço físico, equipe de suporte, compra de hardware, reposição de peças).
- Maior eficiência na gestão de dados e processos logísticos.
- Aumento da segurança e confiabilidade dos sistemas corporativos com backups automáticos, criptografia nativa e compliance com padrões de saúde/farmacêuticos (HIPAA, LGPD).
- Escalabilidade para sustentar o crescimento da Abstergo como hub de distribuição e futura revendedora digital para farmácias e empresas parceiras.

Recomenda-se a continuidade do plano de transformação digital da Abstergo com a adoção de novas tecnologias em etapas futuras, conforme [roadmap](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/Roadmap.md) em anexo. Além disso, os compromissos, responsabilidades e métricas de desempenho referentes à implementação e manutenção dos serviços AWS contratados pela Abstergo Industries encontram-se no [Termo de Acordo de Nível de Serviço (SLA)](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/SLA.md).

## Anexos
- [Estimativa de Custos com AWS](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/Estimativa%20de%20Custos.md)
- [AWS Pricing Calculator com PostgreSQL](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/AWS_Pricing_Calulator_Abstergo_PostgreSQL_v1.pdf)
- [AWS Pricing Calculator com MySQL](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/AWS_Pricing_Calulator_Abstergo_MySQL_v1.pdf)
- [AWS Pricing Calculator com DynamoDb](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/AWS_Pricing_Calulator_Abstergo_DynamoDB_v1.pdf)
- [Roadmap de Adoção AWS – Abstergo Industries](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/Roadmap.md)
- [Termo de Acordo de Nível de Serviço (SLA)](https://github.com/estherdefreitas/relatorio-farmacia-aws/blob/main/SLA.md)


