# Liga de Computação em Nuvem · Material

Material didático da **Liga de Computação em Nuvem da PUCRS** (Escola Politécnica), grupo
ligado ao programa **AWS Student Builder Group**. Aqui ficam os slides de cada aula, os
desafios práticos e os simulados da certificação **AWS Certified Cloud Practitioner (CLF-C02)**.

## Sobre a Liga

A Liga é um projeto de extensão que leva computação em nuvem para a prática: workshops com
teoria e hands-on, preparação para certificação e projetos com casos reais.

- **Encontros:** quintas-feiras, das 15h30 às 17h
- **Local:** PUCRS, prédio 32, sala 517
- **Público:** graduação em Ciência da Computação, Engenharia de Software, Sistemas de
  Informação, Ciência de Dados e IA e Engenharia de Computação

O semestre é dividido em ciclos: onboarding e ferramentas, trilha de certificação CLF-C02 e
cases com clientes, trabalhados em squads.

## Estrutura do repositório

```
handbook/     handbook do membro (regras, ciclos, como participar)
aulas/        slides de cada encontro, em PDF
desafios/     enunciado e guia de cada desafio prático
simulados/    simulados da CLF-C02
```

## Handbook

[`handbook/liga-nuvem-handbook-2026-2.pdf`](handbook/liga-nuvem-handbook-2026-2.pdf): o guia do
membro para o semestre 2026/2. Comece por ele.

## Aulas

Da aula 02 em diante, os decks seguem os domínios do exame CLF-C02.

| # | Aula | Conteúdo |
|---|---|---|
| 01 | [Encontro inaugural](aulas/01-encontro-inaugural.pdf) | Abertura da Liga: proposta, ciclos do semestre e ecossistema do AWS Student Builder Group (Skill Builder, Credly, Meetup). |
| 02 | [Introdução ao ecossistema da AWS](aulas/02-introducao-aws.pdf) | De on-premise a on-demand, infraestrutura global (regiões, AZs, edge), S3, EC2, Docker e IAM, com hands-on subindo backend e frontend. |
| 03 | [Armazenamento e banco de dados](aulas/03-armazenamento-e-banco-de-dados.pdf) | S3, EBS, EFS, FSx, Storage Gateway, RDS, Aurora, DynamoDB, ElastiCache, Redshift, DocumentDB e Neptune. |
| 04 | [Computação e integração](aulas/04-computacao-e-integracao.pdf) | EC2, Lambda, ECS, EKS, Fargate, Elastic Beanstalk, Lightsail, Batch, SQS, SNS, EventBridge e Step Functions. |
| 05 | [Redes e monitoramento](aulas/05-redes-e-monitoramento.pdf) | VPC, Route 53, CloudFront, API Gateway, Direct Connect, ELB, CloudWatch, CloudTrail, X-Ray e Config. |
| 06 | [Segurança e conformidade](aulas/06-seguranca.pdf) | IAM, KMS, Cognito, WAF, Secrets Manager, Shield e GuardDuty. |
| 07 | [DevOps e analytics](aulas/07-devops-e-analytics.pdf) | CodeCommit, CodeBuild, CodeDeploy, CodePipeline, CloudFormation, Athena, Glue, EMR, Kinesis e QuickSight. |
| 08 | [IA e machine learning](aulas/08-ia-e-machine-learning.pdf) | Rekognition, Comprehend, Textract, Bedrock e SageMaker. |
| 09 | [Well-Architected e Cloud Adoption Framework](aulas/09-well-architected-e-caf.pdf) | Os seis pilares do Well-Architected, as seis perspectivas do Cloud Adoption Framework e os planos de suporte. |
| 10 | [Outros serviços](aulas/10-outros-servicos.pdf) | Serviços que caem na prova só pelo nome: governança, usuário final, migração e custos, com pegadinhas e flashcards. |

## Desafios

Cada desafio traz um cliente fictício com um problema real de nuvem. O **enunciado** descreve a missão e os critérios de entrega; o **guia** mostra um caminho de resolução, passo a passo.

| # | Desafio | O que se pratica | Arquivos |
|---|---|---|---|
| 01 | Dojo Digital | Deploy de uma API em Docker numa EC2, com PostgreSQL via Docker Compose e o frontend como SPA no S3. Extra: VPC Endpoint para o S3. | [enunciado](desafios/01-dojo-digital/enunciado.pdf) · [guia](desafios/01-dojo-digital/guia.pdf) |
| 02 | A Casa Sempre Ganha (GiroBet) | Alta disponibilidade com Application Load Balancer, Auto Scaling Group em várias AZs e Security Groups encadeados. | [enunciado](desafios/02-girobet/enunciado.pdf) · [guia](desafios/02-girobet/guia.pdf) |
| 03 | A Caixa de Lembranças | Chat com RAG sobre as lembranças da família: S3, EC2 autenticada por IAM Role e Amazon Bedrock. | [enunciado](desafios/03-caixa-de-lembrancas/enunciado.pdf) · [guia](desafios/03-caixa-de-lembrancas/guia.pdf) |

> Tente resolver pelo enunciado antes de abrir o guia.

## Simulados CLF-C02

Cinco simulados autorais com **65 questões cada** (325 no total, sem repetição entre eles),
com gabarito e explicação de cada alternativa. A distribuição segue os pesos oficiais do exame:

| Domínio | Peso | Questões |
|---|---|---|
| D1 · Cloud Concepts | 24% | 16 |
| D2 · Security and Compliance | 30% | 19 |
| D3 · Cloud Technology and Services | 34% | 22 |
| D4 · Billing, Pricing, and Support | 12% | 8 |

[Simulado 01](simulados/simulado-clf-c02-01.pdf) · [Simulado 02](simulados/simulado-clf-c02-02.pdf) · [Simulado 03](simulados/simulado-clf-c02-03.pdf) · [Simulado 04](simulados/simulado-clf-c02-04.pdf) · [Simulado 05](simulados/simulado-clf-c02-05.pdf)

Faça em 90 minutos, sem consulta, como no exame. A nota de aprovação da CLF-C02 é 700 de 1000.

## Links úteis

- [AWS Skill Builder](https://skillbuilder.aws/)
- [Guia do exame CLF-C02](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.html)
- [AWS Builder Center](https://builder.aws.com/)

---

Material produzido pela Liga de Computação em Nuvem da PUCRS para uso dos membros.
