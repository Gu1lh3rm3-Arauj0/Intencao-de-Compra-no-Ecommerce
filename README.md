# Projeto Final de Machine Learning II - Santander Coders
Detecção de Intenção de Compra no E-commerce e Clusterização das Sessões com Conversão

## Contexto
O aumento do uso do E-commerce nos últimos anos criou novas oportunidades de mercado, mas as taxas de conversão não acompanharam esse crescimento, gerando a necessidade de soluções que ofereçam promoções personalizadas aos consumidores online. No varejo físico, vendedores usam sua experiência para influenciar as taxas de conversão e vendas, e as empresas de E-commerce precisam investir em sistemas de detecção precoce e previsão comportamental para imitar esse comportamento de forma online.
</br></br>

## Descrição do Dataset
Este projeto utiliza um dataset sintético denominado ["Online Shoppers Purchasing Intention"](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset), disponibilizado por Sakar e Kastro (2018), que consiste nos dados de um varejista online. O conjunto de dados consiste em vetores de características de 12.330 sessões, sendo que cada sessão pertence a um usuário diferente em um período de 1 ano, para evitar tendências específicas de campanhas, dias especiais, perfis de usuários ou períodos.
</br></br>

### Visão Geral do Dataset
- **Número de Sessões**: 12,330
- **Características**: 18
- **Sessões com conversão**: Aproximadamente 15%
</br></br>

### Detalhes das Variáveis
#### Variáveis numéricas
- **Administrative**: Número de páginas de gerenciamento da conta visitadas.
- **Administrative_Duration**: Tempo (seg) de permanência em páginas de gerenciamento da conta.
- **Informational**: Número de páginas visitadas sobre o site, comunicação e informação de endereço.
- **Informational_Duration**: Tempo (seg) de permanência em páginas sobre o site, comunicação e informação de endereço.
- **ProductRelated**: Número de páginas visitadas relacionadas a produtos.
- **ProductRelated_Duration**: Tempo (seg) de permanência em páginas relacionadas a produtos.
- **BounceRates****: Porcentagem média de visitantes que entram no site por uma página e saem sem realizar outras ações.
- **ExitRates****: Porcentagem média de visualizações de uma página específica que foram as últimas na sessão.
- **PageValues****: valor médio de uma página que o usuário visitou antes de completar uma transação de e-commerce
- **SpecialDay**: Indicador da proximidade do momento da visita a um dia especial (por exemplo, Dia das Mães, Dia dos Namorados).
</br></br>

** As variáveis "BounceRate," "ExitRate," e "PageValue," são métricas medidas pelo "Google Analytics" para cada página do site de E-commerce e podem ser armazenadas no banco de dados do aplicativo e atualizadas automaticamente em intervalos regulares.
</br></br>

#### Variáveis categóricas
- **Month**: Mês da data da visita.
- **OperatingSystems**: Sistema Operacional utilizado pelo visitante.
- **Browser**: Browser utilizado pelo visitante.
- **Region**: Região geográfica de onde a sessão foi iniciada pelo visitante.
- **TrafficType**: Tipo de tráfego pelo qual o visitante chegou ao site (por exemplo, banner, SMS, direto).
- **VisitorType**: Tipo do visitante (Novo, Retornante ou Outro).
- **Weekend**: Indicador binário se a data da visita é ou não um fim de semana.
- **Revenue (Target)**: Indicador se a visita foi finalizada com uma transação ou não.
</br></br>

## Objetivos do Projeto
1) Entender o problema de negócio ao qual o dataset escolhido se insere.

2) Desenvolver  uma análise de segmentação das sessões que terminaram em conversão, a partir de agrupamentos no conjunto de dados.

3) Desenvolver um modelo de machine learning capaz de identificar as sessões com conversão em dados de e-commerce.
</br></br>

Estes objetivos buscam entender os diferentes tipos de sessões que obtiveram sucesso na venda, e também servir como uma ferramenta para melhorar as taxas de conversão do E-commerce, auxiliando na criação de soluções que ofereçam promoções personalizadas aos consumidores online.
</br></br>

## Estrutura do Projeto
Para atingir os objetivos do projeto este notebook seguirá os seguintes passos para abordar o problema de detecção de fraudes:
1. Análise Exploratória de Dados (EDA) para entender as características e a distribuição das sessões.
2. Clusterização dos dados para análise de diferentes tipos de sessões com conversão.
3. Comparação de diferentes modelos de classificação para identificar o mais eficaz na detecção de conversão.
</br></br>

## Contato

Para dúvidas ou sugestões, por favor, entre em contato com algum dos membros do grupo:

- Laura
- Guilherme Araujo
- Guilherme Almeida
- Carlos Eduardo
- Luiz Henrique

Professor: Tiago Marto
