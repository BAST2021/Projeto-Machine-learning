#  Neste projeto  foi criado um Detector de Fraudes

Mais o que seria um Detector de Fraudes?
-
Pense no detector de fraudes como um "vigilante digital" muito esperto. Ele observa todas as transações de cartão de crédito e tenta identificar se algo não parece certo. Para fazer isso, ele usa um tipo de inteligência artificial chamada machine learning (ou aprendizado de máquina). 

Por Que é Importante?
Esse detector ajuda a proteger pessoas e empresas contra fraudes, evitando que dinheiro seja roubado ou que informações pessoais sejam comprometidas. É como ter um especialista que nunca dorme, sempre atento para identificar e bloquear atividades fraudulentas!

Para um melhor entendimento foi traduzidas a features (Características) dos dados coletados, foi feita uma análise estatística , após foi verificados a quantidade de fraudes que ouve  nos dados , foram 116 fraudes ao total.


### Agora neste momento foi usado uma ferramenta de  análise exploratória  de dados do Python que é o Pandas Profiling  , nos dado:
1. Análise Rápida e Abrangente:
•	Resumo Estatístico: O Pandas Profiling gera um relatório detalhado com estatísticas descritivas sobre cada coluna dos seus dados, como média, mediana, desvio padrão e valores únicos.
•	Distribuições de Dados: Ele mostra histogramas e gráficos de distribuição para ajudar a visualizar como os dados estão distribuídos.
2. Identificação de Problemas de Dados:
•	Valores Ausentes: Identifica a quantidade e a porcentagem de dados ausentes em cada coluna, ajudando a detectar problemas de dados incompletos.
•	Duplicatas: Detecta registros duplicados, o que pode ser crucial para garantir a qualidade dos dados.
•	Outliers: Identifica valores atípicos que podem impactar negativamente na análise.
3. Insights Visuais:
•	Gráficos e Tabelas: Gera gráficos e tabelas que tornam mais fácil compreender padrões e características dos dados, como correlações entre variáveis.
•	Correlação: Mostra a matriz de correlação, que ajuda a entender as relações entre diferentes variáveis.


Agora neste momento foi utilizado a o Enconding  para deixar todos os dados para que não ocorra erros na hora de passar pro um processo de machine learning e após foi retirada 3 features que não são uteis para os processos de machine learning  .

Foi escolhido 3 modelos de machine learning para ver qual apresentaria melhores dados para o detector de fraudes. e estes são os modelos de machine learning: 

- 1º Regressão logística 
- 2º Arvore de decisão 
- 3º Random Forest

 Após aplicar cada modelo de machine learning, geramos dados estatísticos (Acurácia , Precisão , Recall e F1) , Matriz de confusão  para ver como cada modelo estaria se comportando , e após passei os dados por uma balanceamento deixando o  dados os  50/50 que seria 50% dos dados como fraude e os outros 50 % como não fraude.
Agora neste momento foi aplicado novamente  pelo modelo de machine learning para ver qual modelo apresentaria melhor sem nenhum viés .

### O modelo de machine learning que melhor performou foi  Random Forest .

Matriz de confuzão do Random Forest

![arda](https://github.com/user-attachments/assets/ef9a4008-2684-4130-bf10-e5cf79a13424)


- Acurácia: 99,13%

- Precisão: 99,11%

- Recall: 99,15%

- F1: 99,13% 




