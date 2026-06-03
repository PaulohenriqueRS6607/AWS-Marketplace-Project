Este projeto realiza uma análise exploratória de avaliações de clientes em um marketplace de e-commerce, buscando compreender 
a relação entre as notas atribuídas e os comentários textuais. A análise identifica padrões de satisfação, tendências de comportamento e possíveis inconsistências
entre avaliações numéricas e sentimentos expressos, utilizando gráficos e visualizações para gerar insights que apoiem melhorias em produtos, serviços e na experiência do consumidor.


Estrutura do projeto:

Seção 0 → Configuração do Ambiente (Instalações, imports e configurações)
Nesta seção foram feitos os imports de bibliotecas como pandas, numpy, matplotlib e seaborn, implementação de bibliotecas relacionadas a análise de sentimento como VADER,LeIA, Textblod e Transforms e criação de funções auxiliares como manipulação de textos, classificação de sentimento e algoritmos de ordenação.

Seção 1 → Carregamento e diagnóstico do banco (Leitura do banco Estrutura, tipos e qualidade dos dados)
Nesta seção foram feitos os carregamentos das tabelas, resumo da saúde do banco de dados, implementação do modelo relacional que mostra a organização das tabelas dentro do banco de dados suas conexões e cardinalidades, assim como o dicionário de dados.

Seção 2 → Limpeza e tratamento dos dados(Tratamento de nulos, ajuste de tipos e padronizações)
Nesta seção foi feito o tratamento e limpeza dos dados.

Seção 3 → Análise Exploratória das Avaliações(Distribuição das notas Junção/concatenação dos comentários, primeiros insights)
Nesta seção foi feita a análise da tabela df_avaliacoes e a visualização da distribuição de texto nas avaliações com um gráfico em barra, focando no ponto central do projeto.

Seção 4 → Investigação da Coerência entre Nota e Comentário(Identificação do problema de inconsistência e casos divergentes)
Nesta seção foi mostrado um problema que existe no banco de notas altas com comentários negativos e o oposto disto. Também foi mostrada em forma de gráfico de barra a distribuição das avaliações de texto.

Seção 5 → Análise de sentimento (VADER, LeIA, Transforms)
Nesta seção foi iniciada a análise de sentimento utilizando VADER,LeIA e Transforms. Foi feita também gráficos para visualização dos modelos.

Seção 6 → Comparação entre modelos(Métricas, concordância entre resultados, escolha do modelo mais adequado)
Nesta seção foi feita a comparação de desempenho entre os modelos para entender qual deles era o mais confiável para avaliações em português e foi feita a visualização das comparações com gráficos.

Seção 7 → Análise Textual Complementar (Emojis, frequência de palavras e Word Cloud)
Nesta seção foi feita a análise de emojis e wordcloud verificando o impacto deles nas pontuações e foram exploradas paralvras mais presentes nas avaliações inconsistentes.

Seção 8 → Índice de confiabilidade por vendedor(Cálculo do índiceordenação, insights finais)
Nesta seção foi transformada a análise de texto em um insight de negócio. Cruzamos as inconsistências detectadas pelos modelos com os vendedores, gerando um índice de confiabilidade que indica quais vendedores têm maior discrepância entre a nota recebida e o sentimento real dos comentários.

Também comparamos o Selection Sort implementado manualmente com o .sort_values() nativo do pandas, evidenciando o trade-off entre compreensão pedagógica e eficiência computacional.
