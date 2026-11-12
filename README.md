# Módulos Terraform — ToggleMaster

Este repositório contém os módulos Terraform reutilizáveis extraídos da infraestrutura da Fase 2.

## Módulos

Os módulos de networking, ECR, EKS, IAM/IRSA, RDS, ElastiCache, SQS e DynamoDB ficam na raiz, um diretório por módulo.

O repositório `toggle-master-terraform-infra` consome estes módulos por fontes Git fixadas em uma tag de release. Publique uma tag revisada antes de atualizar a referência na infraestrutura. Não armazene state do Terraform, credenciais ou arquivos `.tfvars` reais aqui.
