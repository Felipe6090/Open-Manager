
### Início
### Funcionalidades comuns do ERP

Aqui gostaria de mostrar algumas funcionalidades que serão vistas em todo o ERP:
##### Filtros E Minimizar Painel
Ao passar o mouse no canto superior direito, você pode escolher as opções de filtro ou minimizar o painel

![[Pasted image 20250517170610.png]]
#### Tabelas
Várias telas do Open Manager têm como padrão de visualização o uso de tabelas, veja abaixo funcionalidades comuns entre elas 
![[Pasted image 20250517181146.png]]


#### GED

GED (Gestão Eletrônica de Documentos) é um sistema que digitaliza, organiza e gerencia documentos, tornando-os acessíveis através de um sistema eletrônico. Alguns dados no Open Manager podem receber esse tipo de arquivo. Exemplos: [[conta à pagar]]
#### Relacionamento
Relacionamentos é como o Open Manager gerencia hierarquias de categorias. Veja um exemplo:

Temos 3 registros de Categorias Financeiras e seus Relacionamentos abaixo:
- DESPESAS NÃO OPERACIONAIS
![[Pasted image 20250518125252.png]]


- AQUISIÇÃO DE IMOBILIZADO
![[Pasted image 20250518125435.png]]

- Computadores e acessórios
![[Pasted image 20250518125606.png]]

Esses 3 juntos produzirão, em Financeiro->Categorias Financeiras->Despesas, o seguinte resultado:
![[Pasted image 20250518125926.png]]

## Dashboard
O dashboard irá te dar um resumo de dados em forma de gráficos e tabela. Vejamos quais são:
### Balanço Financeiro
Resumo do balanço financeiro da empresa

![[Pasted image 20250516195437.png]]
#### Contas a receber:
- Recebidas
- Vencidas 
- Em aberto
#### Resultado Financeiro do Mês:
- Contas Pagas
- Contas Recebidas
#### Contas a Pagar:
- Pagas
- Vencidas
- Em Aberto
#### Opções de filtro:
- Data Vencimento Início
- Data Vencimento Fim
### Análise financeira do mês
O gráfico de analise financeira, foi desenvolvido para o gestor financeiro ter em um único ambiente os valores já compilados para uma analise do mês dia a dia.

![[Pasted image 20250516195501.png]]
#### Gráfico:
Dia x Valor (R$)
#### Opções de filtro:
- Mês Base
### Detalhamento Recebimentos/Contas a paga

![[Pasted image 20250516195541.png]]

#### Detalhamento dos recebimentos
Detalhamento das Receitas em um gráfico dinâmico.
- ID
- Categoria Financeira
- Total (R$)
- Total (%)
#### Detalhamento contas a pagar
Detalhamento gráfico das despesas da empresa acumuladas para o mês.
- ID
- Categoria Financeira
- Total (R$)
- Total (%)
#### Opções de filtro:
- Data Início
- Data Fim

### Análise de vendas por período
O gráfico de analise de vendas por período foi desenvolvido para o gestor financeiro ter assim, num único ambiente, os valores da receita de vendas já compilados para uma analise por período.

![[Pasted image 20250516195615.png]]
#### Gráfico
- Data (dia/mês) x Qtd. de Vendas
#### Opções de filtro:
- Data Início
- Data Fim
- Tipo de amostra
	- Por Valor
	- Por Qtd.
- Tipo de Período
	- Diário
	- Mensal
	- Anual


### Análise de vendas em tempo real por PDV
O gráfico de análise de vendas em tempo real, foi desenvolvido para o gestor financeiro ter em um único ambiente os valores da receita de vendas para uma análise em tempo real.

Ainda não está completo!!!

![[Pasted image 20250516203339.png]]
#### Gráfico:
- Tempo (horas) x Qtd. de Vendas
#### Opções de filtro:
- Nome do PDV
- Tipo de Amostra
	- Por Valor
	- Por Quantidade
- Intervalo de tempo (5 - 60 minutos)
- Tempo Real (Sim/Não)



### Curva ABC - Gráfico de Pareto
Desfrute de uma metodologia centenária. O Gráfico de Pareto para analisar o seu negocio como um todo.  O Pareto, conhecido também como 80/20, é uma das técnicas mais difundidas de problem solving.

É um gráfico de colunas que ordena as frequências das ocorrências, da maior para a menor, permitindo a priorização dos problemas.

![[Pasted image 20250516204453.png]]
#### Gráfico:
Problema Identificado x Qtd. de Ocorrências
#### Opções de filtro:
- Data Inicial
- Data Fim
- Origem
	- Vendas
	- Pedidos de Vendas
- Modalidade
	- Clientes
	- Produtos
- Tipo
	- Faturamento
	- Lucratividade


### Previsibilidade de Impostos
Previsibilidade de impostos que sua empresa pagará até o momento.

![[Pasted image 20250516204739.png]]
#### Dados:
- Período
- Faturamento
- Imposto total previsto
	- ICMS
	- ISS
	- PIS
	- COFINS


### Listagem de Produtos mais/menos vendidos
Listagem dos Produtos mais/menos vendidos.

![[Pasted image 20250516204945.png]]
#### Tabela:
- ID
- Produto
- Quantidade
- Receita (R$)
- Estoque
#### Opções de filtro:
- Data Inicial
- Data Final
- Tipo de Amostra
	- Mais Vendidos
	- Menos Vendidos
- Tamanho da Amostra (15 - 60 Produtos ou Todos eles)
- Origem
	- Venda
	- Pedido de Venda

### Total de Ordens de Serviço
Gráfico para analise geral de Ordens de Serviço

![[Pasted image 20250516214957.png]]
#### Gráfico:
Data (dia/mês/ano) x Qtd. de OS´s
- Aguardando
- Finalizada
- Cancelada
- Em atendimento
- Aguardando Cliente
- Aguardando Peça
- Processo Terceirizado
#### Opções de filtro:
- Data Inicial
- Data Final
- Tipo de Amostra
	- Qtd.
	- Valor
- Tipo de Período
	- Diário
	- Mensal
	- Anual




### Total de O.S. por Técnico
Gráfico para analise de Ordens de Serviço. Aqui você verá o Total de O.S por Técnico

![[Pasted image 20250516215928.png]]
#### Gráfico:
Qtd. de OS´s x Técnico 
- Técnico
- N° de OS

Legenda:
- Azul Aberto
- Verde - Fechado

#### Opções de filtro:
- Data Inicial
- Data Final
- Tipo de Amostra
	- Qtd.
	- Valor (R$)

### Análise do Vendedor
Análise por vendedor

![[Pasted image 20250516221852.png]]

#### Dados Mostrados:
- Clientes na Carteira
- Cidades Atendidas
- Clientes Abertos
- Novos Produtos
- Ultima Venda
- Clientes Positivados
- Clientes sem Vendas
- Ticket Médio

#### Opções de filtro:
- Data Inicial
- Data Final
- Origem
	- Vendas
- Vendedores



### Ranking de vendedores
Gráfico para análise geral do desempenho dos vendedores em tempo real.

![[Pasted image 20250516222404.png]]
### Gráfico:
Valor (R$) x Vendedor

Legenda:
- Azul - Orçamento
- Laranja - Pedido de Venda
- Verde - Venda
#### Opções de Filtro
- Data Inicial
- Data Final
- Vendedores
- Tipo de Amostra
	- Qtd.
	- Valor (R$)


### Clientes sem atividades
Ferramenta para verificar a quanto tempo o cliente não realiza compra e auxiliar na inserção das atividades do CRM.

![[Pasted image 20250516223257.png]]
#### Tabela:
- Código
- Nome
- Responsável
- Vendedor
- Telefone
- E-mail
#### Opções de Filtro
- Tempo (dias)
- Vendedores
- Origem
- Verificar agendamento (Sim/Não)

### Mapa de Vendas
Mapa de vendas com quantidade de vendas efetuadas.
![[Pasted image 20250516224810.png]]
#### Tabela:
- UF
- Total (R$)
#### Mapa - Temperatura de Venda
#### Opções de Filtro
- Data Inicial
- Data Final
- Origem
	- Orçamento
	- Pedido de Venda
	- Venda
- Vendedores
- Tipo de Produto
	- Sem Filtro
	- Grupo de Produto
	- Marca


### Mapa de Oportunidades
Mapa de vendas com quantidade de vendas efetuadas.

![[Pasted image 20250516231620.png]]
#### Legenda:
- Branco - Baixa
- Azul Claro - Média
- Azul Escuro - Alta
#### Estatísticas de Vendas:
- Total de Vendas (R$)
- Total de Clientes
- Estados Atendidos
- Municípios Atendidos
#### Opções de Filtro:
- Data Inicial
- Data Final
- Origem
	- Orçamento
	- Pedido de Vendas
	- Vendas

### Performance de Vendas
Com o proposito de apresentar os números realizados em função das metas programadas por vendedores abstraído do mês corrente. Deixe sua equipe de vendas em dias.
#### Fazer depois
#### Opções de Filtro:
- Data
- Origem
	- Orçamento
	- Pedido de Venda
	- Vendas
- Vendedores


### Gráfico de Metas
Com o proposito de apresentar ao gestor uma direção quanto aos números realizados em função das metas programadas, o Gráfico Spider realiza um comparativo entre os números de acordo com o filtro. Deixe sua equipe de vendas em dias.

![[Pasted image 20250516235052.png]]
#### Legenda:
- Azul - Meta
- Laranja - Realizado
#### Opções de Filtro:
- Data Inicial
- Data Final
- Origem
	- Orçamento
	- Pedidos de Vendas
	- Vendas
- Vendedores

### Produção por Grupo de Produto
Gráfico para análise geral do desempenho da Produção por grupo de produto.

![[Pasted image 20250516235208.png]]
#### Gráfico: 
- Programado x Realizado
#### Legenda:
- Azul Escuro - Programado
- Azul Claro - Realizado
#### Opções de Filtro:
- Data Inicial
- Data Final
- Grupo

### Produção Diária
Gráfico para análise geral do desempenho da Produção em Tempo Real.

![[Pasted image 20250517001057.png]]
#### Gráfico:
Processo x Qtd. Programados/Realizados

#### Legenda:
- Roxo - Programado
- Azul - Realizado
#### Opções de Filtro:
- Data Inicial
- Data Final
- Processos

### Vendas por região
Gráfico para análise de vendas por região de clientes.
![[Pasted image 20250517001424.png]]

#### Opções de Filtro:
- Data inicial
- Data Final