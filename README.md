# Análise Exploratória de Cancelamentos de Clientes
Este repositório contém uma análise exploratória de dados (EDA) focada em entender os motivos de cancelamento de clientes em uma empresa com mais de 800 mil clientes. O objetivo principal é identificar os principais fatores que levam ao cancelamento e propor ações eficazes para reduzir essa taxa.

# Descrição do Projeto:
A empresa identificou que a maioria de sua base de clientes é inativa, ou seja, já cancelou o serviço. Para melhorar seus resultados, a empresa deseja entender os principais motivos desses cancelamentos e quais ações podem ser tomadas para reduzir esse número.

**Dados Utilizados:**
O conjunto de dados utilizado contém informações sobre os clientes, incluindo:

**- CustomerID**: Identificador único do cliente.

**- idade**: Idade do cliente.

**- sexo**: Gênero do cliente.

**- tempo_como_cliente**: Tempo que o cliente está com a empresa.

**- frequencia_uso**: Frequência com que o cliente utiliza o serviço.

**- ligacoes_callcenter**: Número de ligações feitas ao call center.

**- dias_atraso**: Dias de atraso no pagamento.

**- assinatura**: Tipo de assinatura do cliente (Basic, Standard, Premium).

**- duracao_contrato**: Duração do contrato (Monthly, Quarterly, Annual).

**- total_gasto**: Total gasto pelo cliente.

**- meses_ultima_interacao**: Meses desde a última interação com o cliente.

**- cancelou**: Indicador se o cliente cancelou o serviço (1.0 para cancelou, 0.0 para não cancelou).

**Análise Realizada**

1.**Limpeza dos Dados**:

- Remoção de colunas irrelevantes (CustomerID).
- Remoção de linhas com valores nulos.

2.**Análise de Cancelamentos**:

- Identificação de que 56.7% dos clientes cancelaram o serviço.

- Visualização de histogramas para cada variável, segmentados por clientes que cancelaram e não cancelaram.

3.**Identificação de Padrões**:

- Clientes com contratos mensais tendem a cancelar mais.

- Clientes que ligam mais de 4 vezes para o call center têm maior probabilidade de cancelar.

- Clientes com mais de 20 dias de atraso no pagamento tendem a cancelar.

4.**Propostas de Ações**:

- Contrato: Oferecer descontos maiores para planos anuais e trimestrais.

- Call Center: Resolver problemas dos clientes em até duas ligações.

- Dias de Atraso: Enviar avisos diários após 20 dias de atraso.

- Resultados Após Implementação das Ações:

**Após a aplicação das ações propostas, a taxa de cancelamento caiu para 18.4%, enquanto a taxa de retenção subiu para 81.6%.**

**Visualizações**:
Foram gerados histogramas para cada variável, mostrando a distribuição dos dados e a relação com o cancelamento. Essas visualizações ajudaram a identificar os principais fatores que influenciam o cancelamento.

Conclusão
A análise mostrou que é possível reduzir significativamente a taxa de cancelamento com ações direcionadas, como a melhoria no atendimento ao cliente, oferta de descontos em planos de maior duração e monitoramento mais rigoroso dos pagamentos em atraso
