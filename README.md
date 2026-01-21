# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 02/02/02026

Empresa: Abstergo Industries 

Responsável: Inayara F.

## Introdução
Este relatário apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Inayara F. O objetivo do projeto foi elencar 3 serviçõs AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serÃ£o descritas as etapas do projeto:

Etapa 1: 
- __Amazon S3 + Glacier Instant Retrieval__
- Tem o foco de armazenar arquivos altamente duráveis, pouco acessados, comtém backups e permite escalação, ou seja, aumento de arquivos armazenados.
- Substituem a infraestrutura e TI interno ao lidar com os arquivos duráveis como:
      - Documentos regulatórios
      - Licença de venda
      - Contratos com fornecedores e clientes
      - Histórico de compras
      - Entre outros.
São arquivos de baixa recuperação mensal, acessados por pessoas restritas e que precisam de histórico de alterações rastreavéis. Que foca em elimina locais de infraestrutura, TI interno e outros custos de armazenamento. A ferramenta também exe

Etapa 2: 
- __AWS Lambda + Step Function__
- Ofece uma computação serverless, executando código sob demanda e organiza os fluxos de negócio.
- O sistema AWS irá automaitizar tarefas como: operações de compra, gestão de estoque, e revenda, que estão sujeitas a lidar com preços, regras comerciais, prazos e rastreabilidade dos produtos. Assim, a ferramenta executarias pequenas rotinas de forma automática seguindo regras funcionais de autorização.

Etapa 3: 
- __Amazon RDS__
- Armazenar e gerenciar bancos de dados relacionais gerenciado, e com alta disponilidade.
- Elimina o banco de dados local para um em Cloud. Armazena dados estruturados como pedidos, clientes, estoque e preços. Além disso, a ferramenta de AWS Lambda se alimenta diretamente desses dados e os atulizam em temp real.



## ConclusÃ£o
A implementação de ferramentas na empresa Abstergo Industries tem como esperado redução de custos de infraestruturas locais e automatização de processos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Inayara F.
