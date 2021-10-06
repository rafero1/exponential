# Privacidade Diferencial: Mecanismo Exponencial
O objetivo do projeto é realizar uma implementação de privacidade diferencial utilizando o mecanismo exponencial no dataset de entrada ([Dataset_Covid_CE.csv](Dataset_Covid_CE)). 

Para cada Query, foi criada uma função de score para ser aplicada junto a função exponencial, e para cada valor de epsilon em {0.1, 0.5, 1.0, 10.0} foram realizadas múltiplas consultas para obter uma média dos resultados do algoritmo.

O projeto foi realizado em python no ambiente jupyter notebook, com ajuda das bibliotecas pandas e numpy.