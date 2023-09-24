# Padrão de Clientes de Cartão de Crédito

### Contextualização: 
Nesse projeto  foi feito uma análise de um conjunto de dados relacionado a padrão de clientes de cartão de crédito, entrando nos campos de limite de cartão de crédito, utilização e pagamento com valor em dólar taiwanês (TWD) coletados no período de abril a setembro do ano de 2005. Tendo como fonte do Dataset o [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients).

### Problema: 
Verificar o risco de inadimplência de novos clientes para o fornecimento de cartão de crédito

### Proposta: 
Desenvolver um sistema de machine learning para verificar a probabilidade de ser inadimplente baseando-se nos dados coletados, verificando características em comum entre os clientes que se encontram no estado de inadimplente com os novos clientes.


### Desenvolvedores
 - [Anna Vithoria](https://github.com/AnnaVithoriaMS)
 - [Cláudio Más](https://github.com/claudio-mas)
 - [Oderlan Freire](https://github.com/oderlanfreire)
 
### Tecnologias:
- pandas
- matplotlib
- seaborn
- numpy
- warnings
- pyplot

# Analise Comparativa

### METODOLOGIA : 
Visando encontrar uma solução para o problema de traçar um perfil de novos usuários que possuem risco de serem usuários inadimplentes, foi feita uma análise comparativa de dados, buscando encontrar o melhor tipo de teste como o menor índice de erro.

O tipo abordagem utilizada foi de validação cruzada com K-fold e cinco modelos de teste:
- KNN: K — Nearest Neighbors
- SVM: Support Vector Machine
- Regressão Lógica
- Decision Tree
- Random Forest

COLETA DE DADOS:
Levando em consideração que os dados foram coletados no período de abril a setembro de 2005 em Taiwan e com a moeda sendo o dólar taiwanês. Os dados estão disponíveis na plataforma UC Irvine Machine Learning Repository.