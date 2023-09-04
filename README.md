# Cluster RFM

O desafio é fazer uma análise exploratória da base de lojista de acordo com sua
movimentação financeira, para isso temos uma coluna com a primeira categoria dividida em seis
grupos:
1. Novo (primeira transação = mês de referência), ou seja, é um volume novo em nossa base
de dados;
2. Recorrente (lojista que transacionou mês passado e transacionou no mês de referência);
3. Recuperação (lojista que não transacionou mês passado e transacionou no mês de
referência);
4. Perda (lojista que transacionou mês passado e não transacionou no mês de referência);
5. Churn (lojista que não transaciona a mais de dois meses, baseado no mês de referência);
6. Nunca Mov (lojista que está em nossa base e nunca teve uma transação).

Desafio - sub classificar as categorias da base transacional da Justa.
