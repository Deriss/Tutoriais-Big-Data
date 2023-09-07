# Aplicações de Big Data para a Engenharia Química

## Introdução
A disponibilidade de dados industriais vem crescendo rapidamente, favorecido por ferramentas da Indústria 4.0 como a internet das coisas (IoT) e o aumento da automatização. Esses dados precisam ser obtidos e processados com rapidez para guiar a tomada de decisões. No entanto, devido à quantidade e variedade dos dados obtidos, essa tarefa torna-se cada vez mais complexa. Por esse motivo, técnicas e ferramentas específicas têm sido desenvolvidas para lidar com esse tipo de dados. Apresentaremos alguns exemplos práticos de desafios da engenharia química que podem se ver beneficiados pelo uso destas novas ferramentas.

## Detecção de Falhas

As técnicas de monitoramento geralmente utilizadas na indústria fazem uso de cartas de controle e do Controle Estatístico de Processos para detectar alterações em variáveis chaves do processo. Na maioria dos casos essas técnicas são aplicadas de forma univariada, isto é, olhando para uma única variável por vez. No entanto, nos processos químicos as variáveis geralmente estão altamente relacionadas entre si, motivo pelo qual é necessário ter uma visão mais ampla para poder compreender o estado atual do processo. 
Com esse objetivo, é possível utilizar de forma conjunta os dados provenientes dos diversos sensores instalados nas plantas para detectar falhas ou mudanças nas condições de processos. Existem técnicas baseadas em dados multivariadas que permitem detectar falhas em grandes conjuntos de dados, como a Análise de Componentes Principais (PCA), Partial Least Squares (PLS) e Autoencoders. A partir desses métodos podemos detectar as falhas quando a combinação das variáveis está fora da “normalidade” esperada. Alguns dos desafios atuais nessa área são a não-linearidade dos processos, a presença de múltiplos modos de operação ou a degradação dos modelos com o tempo. 

## Sensores Virtuais

Na maioria dos processos químicos existem variáveis que não podem ser medidas diretamente com facilidade e (ou) rapidez, como por exemplo medições de concentração que requerem de análise laboratorial para serem obtidas. Além disso, medições importantes podem ficar indisponíveis momentaneamente por falhas nos sensores. Nesses casos, o uso de sensores virtuais pode ser útil, já que eles permitem inferir as variáveis desejadas a partir de outras variáveis do processo. Nesse caso, técnicas de regressão multivariada podem ser utilizadas, como Regressão Linear Múltipla, RandomForest, XGBoost ou Redes Neuronais. Estes modelos precisam ser robustos e também devem ser considerados os efeitos da sua degradação com o tempo ou com mudanças na operação quando colocados em produção.

## Plant-wide Control

O Controle Plant-Wide, como o seu nome o indica, procura fazer o design de sistemas de controle que possam otimizar a produção de plantas inteiras, não só de uma única unidade de processamento. Para atingir esse objetivo, é preciso lidar com múltiplos controladores, além de centenas ou milhares de medições. Por esse motivo, ferramentas para extrair, processar e analisar esse volume de dados com rapidez são vitais para esse tipo de controle. Além disso, é preciso entender a hierarquia dos diferentes controladores e detectar quais podem afetar de forma mais significativa a operação. 

## Conclusão


## Referências
