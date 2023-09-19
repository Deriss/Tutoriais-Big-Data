# Dados Tennesse Eastman Process

Esse conjunto de dados é uma adaptação dos dados disponibilizados por [Rieth *et al* (2017)](). Dois datasets são disponibilizados:

- `fault_free_training.csv` contem 500 simulações de 500 observações cada uma contendo dados normais sem falhas. Para cada observação existem 41 variáveis medidas (xmeas_1 a xmeas_41) e 11 variáveis manipuladas (xmv_1 a xmv_11). 
- `faulty_data.csv`contem 100 simulações de 500 observações para cada uma das 20 falhas. As variáveis medidas e manipuladas são as mesmas que no dataset anterior. A variável faultNumber indica o número da falha em cada simulação. Vale destacar que a falha só começa após 1h (20 pontos) do inicio de cada simulação.

![image](https://github.com/Deriss/Tutoriais-Big-Data/assets/47146176/4357f61d-fc70-459e-86fb-027ee7df2132)

## Variáveis
Na seguinte tabela estão especificados os nomes de cada uma das variáveis medidas e manipuladas.

| Variável | Descrição | Unidades | Variável | Descrição | Unidades| Variável | Descrição |Unidades|
| --- | --- | -| --- | --- | -| --- | --- |---|
| xmeas_1 | Alimentação A | kscmh| xmeas_22| Temperatura de saída da água de refrigeração do separador  | ºC| xmv_2   | vazão de alimentação de E |kg/h
| xmeas_2 | Alimentação D | kg/h | xmeas_23| 6A  | %mol| xmv_3   | Vazão de alimentação de A |kscmh
| xmeas_3 | Alimentação E | kg/h| xmeas_24| 6B | %mol| xmv_4   | Vazão de alimentação de A e C | kscmh
| xmeas_4 | Alimentação A e C |kscmh | xmeas_25| 6C | %mol| xmv_5   | Válvula do compressor de reciclo | %
| xmeas_5 | Reciclo |kscmh | xmeas_26| 6D | %mol| xmv_6   | Válvula de purga | %
| xmeas_6 | Vazão de entrada do reator | kscmh | xmeas_27|6E  |%mol | xmv_7   | Vazão de líquido do separador  |m3/h
| xmeas_7 | Pressão no reator | kPa manométrico | xmeas_28| 6F |%mol | xmv_8   | Vazão de líquido do stripper  |m3/h
| xmeas_8 | Nível de líquido no reator | % | xmeas_29| 9A |%mol | xmv_9   | Valvula de vapor do stripper |%
| xmeas_9 | Temperatura do reator | ºC | xmeas_30| 9B |%mol | xmv_10   | Vazão da água de resfriamento do reator  |m3/h
| xmeas_10 | Vazão de purga | kscmh | xmeas_31| 9C |%mol | xmv_11   | Vazão da água de resfriamento do condensador  |m3/h
| xmeas_11 | Temperatura do separador | ºC | xmeas_32| 9D |%mol
| xmeas_12 | Nível de líquido no separador | % | xmeas_33| 9E  |%mol
| xmeas_13 | Pressão no separador | kPa manométrico| xmeas_34| 9F |%mol
| xmeas_14 | Vazão de saída de líquido no separador | m3/h | xmeas_35| 9G  |%mol
| xmeas_15 | Nível de líquido no stripper| %| xmeas_36| 9H |%mol
| xmeas_16 | Pressão do stripper| kPa manométrico | xmeas_37| 11D |%mol
| xmeas_17 | Vazão de saída de líquido do stripper | m3/h | xmeas_38| 11E |%mol
| xmeas_18 | Temperatura do stripper| ºC| xmeas_39| 11F |%mol
| xmeas_19 | Vazão de vapor no stripper | kg/h | xmeas_40| 11G |%mol
| xmeas_20 | Trabalho do compressor  | kW| xmeas_41| 11H |%mol
| xmeas_21 | Temperatura de saída da água de resfriamento do reator | ºC| xmv_1| Vazão de alimentação de D |kg/h


## Falhas
A continuação serão mostradas as diferentes falhas e sua descrição.

| Número de Falha | Descrição |
| --- | -------- |
| Falha 1 |  Degrau na relação A/C da alimentação |
| Falha 2 |  Degrau na compisição de B |
| Falha 3 |  Degrau na temperatura da alimentação de D|
| Falha 4 |  Degrau na temperatura de entrada da água de resfriamento do reator|
| Falha 5 |  Degrau na temperatura de entrada da água de resfriamento do condensador|
| Falha 6 |  Perda da alimentação A|
| Falha 7 |  Perda de pressão no header C|
| Falha 8 |  Variação aleatória da composição da alimentação de A, B e C|
| Falha 9 |  Variação aleatória da temperatura de alimentação de D|
| Falha 10 | Variação aleatória da temperatura de alimentação de C|
| Falha 11 | Variação aleatória da temperatura de entrada da água de resfriamento do reator |
| Falha 12 | Variação aleatória da temperatura de entrada da água de resfriamento do condensador |
| Falha 13 | Desvio lento da cinética do reator |
| Falha 14 | Válvula da água de resfriamento do reator emperrada |
| Falha 15 | Válvula da água de resfriamento do condensador emperrada |
| Falha 16 | Desconhecida|
| Falha 17 | Desconhecida |
| Falha 18 | Desconhecida |
| Falha 19 | Desconhecida |
| Falha 20 | Desconhecida |

## Referências

RIETH, C., AMSEL, B., TRAN, R., COOK, M. **Additional Tennessee Eastman Process Simulation Data for Anomaly Detection Evaluation**. Harvard Dataverse, 2017. Disponível em: [https://doi.org/10.7910/DVN/6C3JR1](https://doi.org/10.7910/DVN/6C3JR1)

MELO, A., CÂMARA, M., CLAVIJO, N., PINTO, J.C. Open benchmarks for assessment of process monitoring and fault diagnosis techniques: A review and critical analysis. **Computers and Chemical Engineering**, v. 165. Elsevier, 2022. Disponível em: [https://doi.org/10.1016/j.compchemeng.2022.107964](https://doi.org/10.1016/j.compchemeng.2022.107964).  
