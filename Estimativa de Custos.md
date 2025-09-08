# Estimativa de Custos Mensais AWS
## 1. Amazon S3 – Armazenamento em Nuvem
**Benefício financeiro:** elimina necessidade de servidores físicos de armazenamento, fitas de backup e manutenção.

**Uso estimado inicial:** 1 TB de dados (documentos, relatórios, histórico de pedidos).

**Custos:**
- Custo médio por GB/mês: ~US$ 0,029.
- Custo mensal: ~US$ 46 (≈ R$ 254).

## 2. Banco de Dados
**Benefício financeiro:** reduz custo com equipe de manutenção de BD, garantindo alta disponibilidade, backups automáticos e escalabilidade.

### 2.1 Relacional - Amazon RDS PostgreSQL
**Configuração inicial:** RDS PostgreSQL db.t3.medium (2 vCPU, 4 GB RAM) + 50 GB de armazenamento SSD + 30 GB de backup.

**Custo:**
- Custo mensal total: ~US$ 124 (≈ R$ 672).
  
### 2.2 Relacional - Amazon RDS MySQL
**Configuração inicial:** RDS MySQL db.t3.medium (2 vCPU, 4 GB RAM) + 50 GB de armazenamento SSD + 30 GB de backup.

**Custo:**
- Custo mensal total: ~US$ 116 (≈ R$ 629).

### 2.3 NoSQL - DynamoDB
**Configuração inicial:** 50GB de armazenamento inicial.

**Custo:**
- Custo mensal total: ~US$ 18 (≈ R$ 97).

## 3. Servidores de Aplicação - Amazon EC2 + Auto Scaling
**Benefício financeiro:** substitui servidores físicos locais, pagando apenas pelo uso e aumentando a capacidade apenas quando necessário (picos de pedidos).

**Configuração inicial:** 1 instância t3.medium

**Custo:**
- Custo mensal: ~US$ 32 (≈ R$ 173).


## Resumo dos Custos Mensais Estimados

| Serviço                           | Custo em USD | Custo em BRL (≈ R$ 5,43/US$) | Observações                                       |
| --------------------------------- | ------------ | ------------------------------ | ------------------------------------------------- |
| **Amazon S3**                     | US\$ 46      | R\$ 120                        | Armazenamento de dados e backups                  |
| **Amazon RDS PostgreSQL**         | US\$ 124     | R\$ 672                        | Banco de dados centralizado                       |
| **Amazon RDS MySQL**              | US\$ 116     | R\$ 629                        | Banco de dados centralizado                       |
| **Amazon DynamoDB**               | US\$ 18      | R\$ 97                         | Banco de dados centralizado                       |
| **Amazon EC2 + Auto Scaling**     | US\$ 32      | R\$ 320                        | Hospedagem e escalabilidade                       |
| **Total Estimado RDS PostgreSQL** | **US\$ 202** | **R\$ 1.112/mês**              | Valores iniciais, escaláveis conforme crescimento |
| **Total Estimado RDS MySQL**      | **US\$ 194** | **R\$ 1.069/mês**              | Valores iniciais, escaláveis conforme crescimento |
| **Total Estimado DynamoDB**       | **US\$ 110** | **R\$ 537/mês**                | Valores iniciais, escaláveis conforme crescimento |

## Análise de Custo-Benefício

Economia inicial prevista:

- Eliminação de servidores locais (estimados R$ 20.000 em aquisição + R$ 2.000/mês em manutenção/energia).
- Redução de equipe de TI dedicada apenas à manutenção de hardware.
- Investimento mensal em AWS gera redução de custos totais de ~50% comparado à infraestrutura tradicional.
- Escalabilidade garantida para expansão conforme aumento de parceiros farmacêuticos e volume de pedidos.
