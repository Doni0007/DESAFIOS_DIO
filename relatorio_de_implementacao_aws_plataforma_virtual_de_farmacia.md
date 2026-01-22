# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 22/01/2026  
Empresa: Abstergo Industries  
Responsável: João Donisete Custódio  

## Introdução
Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **Abstergo Industries**, realizado por **João Donisete Custódio**, com o objetivo de projetar uma plataforma virtual para operação digital da farmácia. A proposta contempla a utilização de três serviços da AWS, priorizando escalabilidade, segurança, alta disponibilidade e redução de custos operacionais.

## Descrição do Projeto
O projeto de implementação da plataforma virtual foi dividido em três etapas, cada uma utilizando um serviço específico da AWS, conforme descrito a seguir:

### Etapa 1:
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Hospedagem e processamento da aplicação da farmácia
- **Descrição de caso de uso:**
O Amazon EC2 foi utilizado para hospedar o backend da plataforma virtual da farmácia, incluindo sistemas de cadastro de clientes, gerenciamento de pedidos, controle de estoque e integração com meios de pagamento. A principal vantagem é a flexibilidade de escalabilidade, permitindo aumentar ou reduzir recursos computacionais conforme a demanda, especialmente em períodos de maior volume de vendas.

### Etapa 2:
- **Nome da ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Armazenamento e gerenciamento de dados transacionais
- **Descrição de caso de uso:**
O Amazon RDS foi adotado para armazenar dados críticos da operação, como informações de clientes, pedidos, produtos e histórico de compras. O serviço oferece alta disponibilidade, backups automáticos e gerenciamento simplificado do banco de dados, reduzindo custos operacionais e riscos de falhas, além de atender requisitos de segurança e confiabilidade exigidos no setor farmacêutico.

### Etapa 3:
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de arquivos e conteúdos estáticos
- **Descrição de caso de uso:**
O Amazon S3 foi utilizado para armazenar imagens de produtos, receitas digitais, documentos fiscais e arquivos de relatórios. O serviço se destaca pelo baixo custo, alta durabilidade e fácil integração com outros serviços da AWS, garantindo acesso rápido e seguro aos dados, além de escalabilidade praticamente ilimitada.

## Conclusão
A implementação dos serviços AWS na empresa **Abstergo Industries** tem como resultado esperado maior eficiência operacional, redução de custos com infraestrutura física, aumento da segurança dos dados e maior disponibilidade da plataforma virtual. A adoção de uma arquitetura em nuvem permite que a farmácia acompanhe o crescimento do negócio de forma sustentável e escalável. Recomenda-se a continuidade do uso dos serviços implementados e a avaliação futura de soluções adicionais, como ferramentas de analytics e machine learning, para aprimorar ainda mais a tomada de decisão.

## Anexos
- Arquitetura lógica da solução em nuvem  
- Documentação técnica dos serviços AWS utilizados  
- Plano de segurança e backup de dados

Assinatura do Responsável pelo Projeto:

**João Donisete Custódio**

