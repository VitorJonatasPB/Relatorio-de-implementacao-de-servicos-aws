# Relatório de implementacao de servicos AWS

**Data:** 05/11/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Vitor Jônatas Paiva Barbosa

## 1. Introdução

Este relatório apresenta uma proposta de implementação de serviços da Amazon Web Services (AWS) na empresa Abstergo Industries, com o objetivo de otimizar a infraestrutura tecnológica e reduzir os custos operacionais relacionados ao armazenamento, processamento e gerenciamento de recursos em nuvem.

O projeto contempla três serviços AWS, selecionados com base na possibilidade de melhorar a utilização dos recursos computacionais, evitar desperdícios e proporcionar maior controle financeiro sobre a infraestrutura.

## 2. Descrição do Projeto

O projeto foi dividido em três etapas, cada uma com objetivos específicos de otimização e redução de custos.

### Etapa 1 — Amazon S3 Intelligent-Tiering

**Foco da ferramenta:** Otimização dos custos de armazenamento de dados.

**Descrição do caso de uso:** A empresa Abstergo Industries possui um volume significativo de documentos, relatórios, imagens e arquivos que são armazenados em nuvem, mas que não são acessados com a mesma frequência.

A implementação do Amazon S3 Intelligent-Tiering permitirá que os arquivos sejam movimentados automaticamente entre diferentes camadas de armazenamento, de acordo com seus padrões de acesso.

Dessa forma, os arquivos frequentemente utilizados permanecem em camadas de acesso rápido, enquanto aqueles pouco acessados podem ser armazenados em camadas de menor custo.

**Benefício esperado:** Redução dos gastos com armazenamento, sem a necessidade de identificar manualmente quais arquivos são acessados com frequência.

### Etapa 2 — Amazon EC2 Auto Scaling

**Foco da ferramenta:** Otimização dos recursos computacionais.

**Descrição do caso de uso:** A empresa utiliza servidores virtuais para executar aplicações e processar informações. Entretanto, manter uma quantidade fixa de servidores ligados durante períodos de baixa utilização pode gerar despesas desnecessárias.

Com o Amazon EC2 Auto Scaling, será possível ajustar automaticamente a quantidade de instâncias EC2 conforme a demanda de processamento.

Durante períodos de maior utilização, novas instâncias poderão ser iniciadas para atender às solicitações. Já em períodos de menor demanda, instâncias excedentes poderão ser encerradas.

**Benefício esperado:** Redução dos custos com servidores ociosos, melhor aproveitamento dos recursos computacionais e manutenção da capacidade necessária para atender aos usuários.

### Etapa 3 — AWS Cost Explorer

**Foco da ferramenta:** Monitoramento e controle dos custos da infraestrutura AWS.

**Descrição do caso de uso:** A empresa necessita acompanhar os gastos relacionados aos serviços contratados na AWS, identificando quais recursos apresentam maior consumo financeiro.

A utilização do AWS Cost Explorer permitirá visualizar os custos por serviço, analisar o histórico de despesas e identificar tendências de crescimento nos gastos.

Com essas informações, a equipe responsável poderá identificar recursos subutilizados, revisar configurações e tomar decisões para otimizar o orçamento destinado à infraestrutura em nuvem.

**Benefício esperado:** Maior controle financeiro, identificação de desperdícios e melhor planejamento dos investimentos em tecnologia.

## 3. Conclusão

A proposta de implementação dos três serviços AWS na empresa Abstergo Industries tem como objetivo principal reduzir os custos operacionais e melhorar a eficiência da infraestrutura tecnológica.

O Amazon S3 Intelligent-Tiering contribuirá para otimizar os custos de armazenamento, o Amazon EC2 Auto Scaling permitirá ajustar os recursos computacionais conforme a necessidade da empresa e o AWS Cost Explorer proporcionará maior visibilidade e controle sobre as despesas.

Com a adoção dessas soluções, espera-se obter melhor aproveitamento dos recursos contratados, redução de desperdícios e maior eficiência na gestão da infraestrutura em nuvem.

Recomenda-se acompanhar periodicamente os resultados financeiros e operacionais para avaliar a economia alcançada e identificar novas oportunidades de otimização.

**Assinatura do Responsável pelo Projeto:** Vitor Jônatas Paiva Barbosa

[Seu nome]
