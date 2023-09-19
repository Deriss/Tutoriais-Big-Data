# Dados Tennesse Eastman Process

Esse conjunto de dados é uma adaptação dos dados disponibilizados por [Rieth *et al* (2017)](). Dois datasets são disponibilizados:

- `fault_free_training.csv` contem 500 simulações de 500 observações cada uma contendo dados normais sem falhas. Para cada observação existem 41 variáveis medidas (xmeas_1 a xmeas_41) e 11 variáveis manipuladas (xmv_1 a xmv_11). 
- `faulty_data.csv`contem 100 simulações de 500 observações para cada uma das 20 falhas. As variáveis medidas e manipuladas são as mesmas que no dataset anterior. A variável faultNumber indica o número da falha em cada simulação. Vale destacar que a falha só começa após 1h (20 pontos) do inicio de cada simulação.

![image](https://github.com/Deriss/Tutoriais-Big-Data/assets/47146176/4357f61d-fc70-459e-86fb-027ee7df2132)

## Variáveis
Na seguinte tabela estão especificados os nomes de cada uma das variáveis medidas e manipuladas.

| Variável | Descrição | | Variável | Descrição || Variável | Descrição |
| --- | --- | -| --- | --- | -| --- | --- |
| xmeas_1 | Alimentação A | | xmeas_22| Temperatura de saída da água de refrigeração do separador  | | xmv_2   | vazão de alimentação de E |
| xmeas_2 | Alimentação D | | xmeas_23| 6A  | | xmv_3   | Vazão de alimentação de A |
| xmeas_3 | Alimentação E | | xmeas_24| 6B | | xmv_4   | Vazão de alimentação de A e C | 
| xmeas_4 | Alimentação A e C | | xmeas_25| 6C | | xmv_5   | Válvula do compressor de reciclo |
| xmeas_5 | Reciclo | | xmeas_26| 6D | | xmv_6   | Válvula de purga |
| xmeas_6 | Vazão de entrada do reator |  | xmeas_27|6E  | | xmv_7   | Vazão de líquido do separador  |
| xmeas_7 | Pressão no reator | | xmeas_28| 6F | | xmv_8   | Vazão de líquido do stripper  |
| xmeas_8 | Nível de líquido no reator | | xmeas_29| 9A | | xmv_9   | Valvula de vapor do stripper |
| xmeas_9 | Temperatura do reator | | xmeas_30| 9B | | xmv_10   | Vazão da água de resfriamento do reator  |
| xmeas_10 | Vazão de purga | | xmeas_31| 9C | | xmv_11   | Vazão da água de resfriamento do condensador  |
| xmeas_11 | Temperatura do separador | | xmeas_32| 9D |
| xmeas_12 | Nível de líquido no separador | | xmeas_33| 9E  |
| xmeas_13 | Pressão no separador | | xmeas_34| 9F |
| xmeas_14 | Vazão de saída de líquido no separador | | xmeas_35| 9G  |
| xmeas_15 | Nível de líquido no stripper| | xmeas_36| 9H |
| xmeas_16 | Pressão do stripper| | xmeas_37| 11D |
| xmeas_17 | Vazão de saída de líquido do stripper | | xmeas_38| 11E |
| xmeas_18 | Temperatura do stripper| | xmeas_39| 11F |
| xmeas_19 | Vazão de vapor no stripper | | xmeas_40| 11G |
| xmeas_20 | Trabalho do compressor  | | xmeas_41| 11H |
| xmeas_21 | Temperatura de saída da água de resfriamento do reator | | xmv_1| Vazão de alimentação de D |


## Falhas
A continuação serão mostradas as diferentes falhas e suas origens:

| Número de Falha | Descrição |
| --- | -------- |
| Falha 1 |   |
| Falha 2 |   |
| Falha 3 |  |
| Falha 4 |  |
| Falha 5 |  |
| Falha 6 |  |
| Falha 7 |  |
| Falha 8 |  |
| Falha 9 |  |
| Falha 10 |  |
| Falha 11 |  |
| Falha 12 |  |
| Falha 13 |  |
| Falha 14 |  |
| Falha 15 |  |
| Falha 16 |  |
| Falha 17 |  |
| Falha 18 |  |
| Falha 19 |  |
| Falha 20 |  |
