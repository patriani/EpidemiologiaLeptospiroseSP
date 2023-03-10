# Trabalho de Conclusão de Curso - Sistemas de Informação na Universidade Federal de Viçosa

Este projeto de pesquisa consiste em uma análise exploratória e descritiva por meio da Mineração de Dados Públicos de Saúde, especificamente de casos de Leptospirose em São Paulo e registrados pelo DATASUS. Para a classificação dos dados foi utilizado o algoritmo Complete Linkage da Clusterização Hierarquica Aglomerativa por meio da linguagem python e biblioteca Scikit Learn.
- O arquivo "amostra_rotulada" possui as seguintes colunas:
   ['Ign/Branco_x', 'Urbana', 'Rural', 'Periurbana', 'Ign/Branco_y','Domiciliar', 'Trabalho', 'Lazer', 'Outro', 'Ign/Branco_z','Analfabeto', '1a4 serie EF incompleto', '4 serie EF completa','5a8 serie EF incompleta', 'EF completo', 'EM incompleto','EM completo', 'ES incompleto', 'ES completo', 'Nao se aplica', 'Total','Cod Mun', 'Municipio', 'Densidade Populacional', 'freq_rel','complete_2', 'geom'], totalizando 27 features;
- As colunas "Ign/Branco_<?>" representam o número de registros em que a pessoa preferiu não responder a pergunta na ficha médica;
- O campo "geom" carrega os limites municipais e devem ser interpretados como sendo do tipo geometry por bancos de dados com extensão geográfica (dados fornecidos pelo IBGE);
- O arquivo uf.csv consiste no limite estadual utilizado para criar visualizações na pesquisa. Também retirado do IBGE.

A apresentação dos resultados foi feita no artigo por meio de gráficos gerados em python e mapas gerados pelo PostgreSQL e QGIS, observar os dois exemplos abaixo:

![Capturar](https://user-images.githubusercontent.com/43487367/218856875-495f8f17-99f8-44ed-bbc3-9f4d2b64edfa.PNG)

![Capturar](https://user-images.githubusercontent.com/43487367/218857283-69911480-3024-4582-92b8-de16b052dfa2.PNG)
