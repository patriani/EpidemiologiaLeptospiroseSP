# GeoDB_Leptospirose
O CSV "amostra_rotulada" é referente à base de dados utilizada na pesquisa científica que compõe meu trabalho de conclusão de curso. A pesquisa consiste em uma análise exploratória e descritiva por meio da Mineração de Dados Públicos de Saúde, especificamente de casos de Leptospirose em São Paulo e registrados pelo DATASUS. Para a classificação dos dados foi utilizado o algoritmo Complete Linkage da Clusterização Hierarquica Aglomerativa por meio da linguagem python e biblioteca Scykit Learn.
- As colunas do documento são: 
   ['Ign/Branco_x', 'Urbana', 'Rural', 'Periurbana', 'Ign/Branco_y','Domiciliar', 'Trabalho', 'Lazer', 'Outro', 'Ign/Branco_z','Analfabeto', '1a4 serie EF incompleto', '4 serie EF completa','5a8 serie EF incompleta', 'EF completo', 'EM incompleto','EM completo', 'ES incompleto', 'ES completo', 'Nao se aplica', 'Total','Cod Mun', 'Municipio', 'Densidade Populacional', 'freq_rel','complete_2', 'geom'], totalizando 27;
- As colunas "Ign/Branco_<?>" representam o número de registros em que a pessoa preferiu não responder a pergunta na ficha médica;
- O campo "geom" carrega os limites municipais e devem ser interpretados como sendo do tipo geometry por bancos de dados com extensão geográfica (dados fornecidos pelo IBGE);
- O arquivo uf.csv consiste no limite estadual utilizado para criar visualizações na pesquisa. Também retirado do IBGE.
