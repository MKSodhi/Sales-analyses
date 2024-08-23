# Sales-Analyses

## Descrição do Projeto: Tratamento e Análise de Dados

### Visão Geral:
Este projeto foca na análise de dados de vendas de uma loja fictícia de eletrônicos. O objetivo é obter insights sobre vários aspectos do negócio por meio da exploração e visualização dos dados. As análises realizadas incluem identificar o melhor mês para vendas, determinar as cidades mais lucrativas, os horários ideais para publicidade, combinações de produtos frequentemente vendidos juntos e os produtos mais vendidos.

### Limpeza e Pré-processamento dos Dados:
O conjunto de dados utilizado para esta análise foi coletado ao longo de vários meses. Antes de realizar qualquer análise, os dados passaram por um processo de limpeza detalhado, incluindo:
- Junção dos dados mensais em um único conjunto de dados.
- Conversão dos tipos de dados para seus formatos apropriados.
- Tratamento de valores ausentes e remoção de inconsistências.
- Extração de informações adicionais, como a cidade do endereço de compra e a hora da data do pedido, para facilitar análises mais detalhadas.

### Perguntas de Negócio Abordadas:
A análise buscou responder às seguintes perguntas-chave:
1. **Qual foi o melhor mês para vendas?** Qual foi a receita gerada durante esse mês?
2. **Qual cidade vendeu mais produtos?** Quais são os fatores que contribuem para essa tendência?
3. **Qual horário deve ser utilizado para exibir anúncios** a fim de maximizar a probabilidade de compra pelos clientes?
4. **Quais produtos são mais frequentemente vendidos juntos?** Entender essas combinações pode ajudar a otimizar estratégias de cross-selling.
5. **Qual foi o produto mais vendido?** Por que ele superou os outros?

### Métodos e Técnicas:
Alguns dos métodos e técnicas utilizados para responder a essas perguntas incluem:
- Agrupamento e agregação de dados para resumir vendas por mês, cidade e hora.
- Visualização de dados com gráficos de barras e linhas para destacar tendências e padrões.
- Utilização de combinações e análise de frequência para descobrir pares de produtos frequentemente vendidos juntos.
- Aplicação de várias bibliotecas Python, como `pandas` para manipulação de dados, `seaborn` e `matplotlib` para visualização de dados, e `itertools` para análise combinatória.

