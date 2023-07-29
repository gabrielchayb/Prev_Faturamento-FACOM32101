PROJETO DE MACHINE LEARNING - REGRESSÃO LINEAR PARA ESTIMAR QUANTIDADE DE VENDAS 

Gabriel Ribeiro Filice Chayb, Universidade Federal de Uberlândia 

Imagina que exista uma empresa que deseja estimar a quantidade de vendas baseado em um investimento que o usuário fornecer com extrema precisão, baseada em campanhas muito similares do passado. De maneira simplista, o modelo analisa esses dados e calcula de maneira gráfica e númerica quantas vendas a empresa irá realizar, além de seu faturamento e retorno sobre o investimento.


Considerações iniciais: Projeto desenvolvido para exemplificar conceitos de Machine Learning e M.P.C para o trabalho de Informática e Ética - FACOM32101 - utiliza-se uma base de dados totalmente fictícia. Todo o algoritmo foi desenvolvido com o objetivo apenas educativo. Portanto, o código é aberto e qualquer pessoa pode utilizá-lo de qualquer maneira.

Introdução: O projeto consiste em prever a quantidade de vendas de um e-commerce caso um valor (R$Y) seja investido em tráfego pago, baseada nos dados das campanhas anteriores desse e-commerce. Assim, utilizei um modelo de regressão linear para efetuar essa previsão com maior acertividade possível e demonstrá-la em um gráfico. Além disso, o algoritmo também calcula o ROI de cada previsão, permitindo diversas simulações para uma melhor tomada de decisão de investimento. 

Métodos: 
1. Bibliotecas Utilizadas; 

Pandas - Tratamento, leitura e manipulação de dados de maneira efetiva; 
Matplotlib - Visualização dos dados em gráfico, tabelas de maneira visual; 
Numpy - Processamento de dados em alto volume e vários tipos;

2. Como funciona o sklearn; 

Sklearn:  

Como uma biblioteca de alto nível, ela permite definir um modelos preditivos de dados em apenas algumas linhas de código. Nesse sentido, o scikit-learn é bem documentado, relativamente fácil de aprender e usar. Ela é ótima para modelos de regressão linear introdutórios ao Data Science e ao Machine Learning.  

Porque o modelo de regressão linear foi escolhido: 

A Regressão linear simples é utilizada em problemas em que queremos identificar um modelo que represente a relação entre duas variáveis, sendo que uma altera o valor da outra de maneira linear. O objetivo é encontrar uma função que expressa essa correspondência. Em sua essência, uma técnica de regressão linear simples tenta traçar um gráfico de linhas entre duas variáveis de dados, x e y. Como variável independente, x é plotada ao longo do eixo horizontal. Variáveis independentes também são chamadas de variáveis explicativas ou variáveis preditoras. A variável dependente, y, é plotada no eixo vertical. Você também pode fazer referência aos valores de y como variáveis de resposta ou variáveis previstas.

Regressão linear simples
A regressão linear simples é definida pela função linear:

Y= β0*X + β1 + ε 

β0 e β1 são duas constantes desconhecidas que representam a inclinação da regressão, enquanto ε (épsilon) é o termo de erro.

Objetivo: Expôr como funciona na prática um projeto que envolva aprendizado de máquinas com poucas linhas de código, relacionando a metodologia de desenvolvimento de um algoritmo M.P.C e os fundamentos do Data Science da maneira mais didática possível: 1. Ciência da computação; 2. Estatística e Matemática; 3. Negócios e B.I;  
