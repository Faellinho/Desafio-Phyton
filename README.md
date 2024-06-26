# Dashboard sobre Combustível

### Rafael Lucas do Nascimento Sales
### Projeto Desenvolve - Itabira
### PDita157

## Título e Descrição Geral

**Desafio Python**  
O código apresenta um dashboard de preços de combustível no Brasil e nos EUA, a quantidade que as pessoas gastam no cartão de crédito com combustível e outros itens usando, e a média da quantidade de CO2 que as marcas de carro de 2022 emitem. Eu escolhi fazer sobre esse tema porque tenho interesse por carros e decidi criar algo relacionado.

## Demonstração de Uso e Instruções para Executar o Projeto

- Primeiro, temos uma caixa de seleção (Selectbox) que muda o tema de todos os gráficos e de uma parte da fonte na sidebar.
- A segunda caixa de seleção (Selectbox) muda a região do Brasil, alterando o segundo gráfico da primeira linha.
- A terceira caixa de seleção múltipla (MultiSelect) muda os estados de acordo com a região selecionada, alterando o segundo gráfico da primeira linha.
- A quarta caixa de seleção (Selectbox) altera o tipo de cartão de crédito, modificando o primeiro gráfico da terceira linha.

**Mude o Arquivo Config.toml para:**  
[theme]  
primaryColor='#262730'  
backgroundColor='#0E1117'  
secondaryBackgroundColor='#262730'  
textColor='#FAFAFA'  
font='sans serif'  


## Tecnologias utilizadas:  
O codigo apresenta as seguintes linguagues:
-  Python
-  Css
-  Html


As bibliotecas utilizadas são:
- Streamlit
- Plotly.express
- Pandas  

## Informações sobre os dados originais:
O Desafio apresenta 5 arquivos CSV  
brazil_fuel.csv - Apresenta os dados do preço do Etanol Hidratado no Brasil de 2004 até 2021, separado por Regiões e estados do Brasil.  

Credit_card_transactions.csv - Apresenta dados das despesas feitas com cartão de crédito, separadas por tipo de cartão de crédito.  

Fuel_Consumption_Ratings.csv - Apresenta dados do consumo de combustível, emissão de CO2 e tamanho do motor, separados por tipo de veículo, modelo e fabricante do veículo.  

PET_PRI_GND_DCUS_NUS_W.csv - Apresenta dados do preço do combustivel separado por:  
A1: Preços semanais de gasolina no varejo para todas as classes e formulações nos EUA (dólares por galão)  
A2: Preços semanais de gasolina convencional no varejo para todas as classes nos EUA (dólares por galão)  
A3: Preços semanais de gasolina reformulada no varejo para todas as classes nos EUA (dólares por galão)  
R1: Preços semanais de gasolina comum no varejo para todas as formulações nos EUA (dólares por galão)  
R2: Preços semanais de gasolina convencional comum no varejo nos EUA (dólares por galão)  
R3: Preços semanais de gasolina reformulada comum no varejo nos EUA (dólares por galão)  
M1: Preços semanais de gasolina de média qualidade no varejo para todas as formulações nos EUA (dólares por galão)  
M2: Preços semanais de gasolina convencional de média qualidade no varejo nos EUA (dólares por galão)  
M3: Preços semanais de gasolina reformulada de média qualidade no varejo nos EUA (dólares por galão)  
P1: Preços semanais de gasolina premium no varejo para todas as formulações nos EUA (dólares por galão)  
P2: Preços semanais de gasolina convencional premium no varejo nos EUA (dólares por galão)  
P3: Preços semanais de gasolina reformulada premium no varejo nos EUA (dólares por galão)  
D1: Preços semanais de diesel nº 2 no varejo nos EUA (dólares por galão)  

**A utilizada foi a R2**

precos_combustiveis.csv - Apresenta dados do preço do combustível de 2012 até 2021, separados por tipo de combustível.  


## Contato:  
Email: rafael.sales@pditabira.com ou Salesrafael2005@gmail.com


