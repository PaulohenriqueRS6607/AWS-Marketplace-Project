# Análise exploratória de dados em Marketplace AWS - O peso das palavras

## Sobre o Projeto

Este projeto realiza uma análise exploratória e de sentimento de avaliações de comentários em um marketplace de e-commerce, com o objetivo de compreender a relação entre as notas atribuídas pelos usuários e os sentimentos expressos em seus comentários.

Através da aplicação de técnicas de análise de dados, processamento de linguagem natural (NLP) e visualização de informações, o projeto busca identificar padrões de satisfação, tendências de comportamento e possíveis inconsistências entre avaliações numéricas e opiniões textuais.

Os resultados obtidos fornecem insights que podem auxiliar na melhoria da experiência do cliente, na avaliação da confiabilidade de vendedores e na tomada de decisões estratégicas para o negócio.

---

# Objetivos

* Analisar o comportamento das avaliações dos clientes.
* Identificar discrepâncias entre notas e comentários.
* Aplicar técnicas de análise de sentimento em português.
* Comparar diferentes modelos de classificação de sentimento.
* Transformar análises textuais em indicadores de negócio.
* Gerar visualizações que facilitem a interpretação dos dados.

---

# Tecnologias utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

# Estrutura do Projeto

## Seção 0 — Configuração do Ambiente

Responsável pela preparação do ambiente de desenvolvimento.

Principais atividades:

* Instalação das bibliotecas necessárias.
* Importação dos módulos utilizados.
* Configuração inicial do notebook.
* Implementação de funções auxiliares para:

  * Limpeza de texto.
  * Classificação de sentimentos.
  * Algoritmos de ordenação.

---

## Seção 1 — Carregamento e Diagnóstico dos Dados

Responsável pela compreensão inicial do banco de dados.

Principais atividades:

* Carregamento das tabelas.
* Verificação da qualidade dos dados.
* Análise de tipos de dados.
* Construção do modelo relacional.
* Identificação das cardinalidades e relacionamentos.
* Apresentação do dicionário de dados.

---

## Seção 2 — Limpeza e Tratamento dos Dados

Etapa dedicada à preparação dos dados para análise.

Principais atividades:

* Tratamento de valores nulos.
* Correção de inconsistências.
* Padronização de formatos.
* Conversão de tipos de dados.
* Ajustes necessários para garantir qualidade analítica.

---

## Seção 3 — Análise Exploratória das Avaliações

Primeira investigação sobre o comportamento das avaliações.

Principais atividades:

* Distribuição das notas.
* Análise dos comentários dos clientes.
* Junção e tratamento dos campos textuais.
* Construção de gráficos exploratórios.
* Geração dos primeiros insights.

---

## Seção 4 — Investigação da Coerência entre Nota e Comentário

Análise das divergências entre avaliação numérica e opinião textual.

Principais atividades:

* Identificação de avaliações inconsistentes.
* Casos de notas altas com comentários negativos.
* Casos de notas baixas com comentários positivos.
* Visualização gráfica das divergências.
* Levantamento de hipóteses sobre o comportamento dos consumidores.

---

## Seção 5 — Análise de Sentimento

Aplicação de modelos de NLP para classificação automática dos comentários.

Modelos utilizados:

* VADER
* LeIA
* Transformers

Principais atividades:

* Classificação dos comentários.
* Comparação dos resultados obtidos.
* Visualização gráfica das distribuições de sentimento.
* Avaliação do comportamento de cada modelo.

---

## Seção 6 — Comparação entre Modelos

Etapa destinada à avaliação dos modelos de análise de sentimento.

Principais atividades:

* Comparação de desempenho.
* Avaliação da concordância entre classificações.
* Identificação do modelo mais adequado para textos em português.
* Construção de gráficos comparativos.

---

## Seção 7 — Análise Textual Complementar

Exploração aprofundada do conteúdo textual das avaliações.

Principais atividades:

* Análise de emojis.
* Frequência de palavras.
* Geração de Word Clouds.
* Investigação dos termos mais frequentes em avaliações inconsistentes.
* Identificação de padrões linguísticos relevantes.

---

## Seção 8 — Índice de Confiabilidade por Vendedor

Transformação dos resultados analíticos em um indicador de negócio.

Principais atividades:

* Cruzamento entre vendedores e avaliações inconsistentes.
* Criação de um Índice de Confiabilidade.
* Identificação de vendedores com maior discrepância entre nota e sentimento.
* Ranking de vendedores baseado na consistência das avaliações.

Além disso, foi realizada uma comparação entre:

* Selection Sort (implementação manual)
* sort_values() (Pandas)

demonstrando a diferença entre abordagens educacionais e soluções otimizadas para ambientes de produção.

---

# Principais Resultados

* Identificação de inconsistências entre notas e sentimentos.
* Avaliação comparativa de modelos de NLP para português.
* Descoberta de padrões textuais associados à insatisfação dos clientes.
* Desenvolvimento de um índice de confiabilidade para vendedores.
* Geração de insights estratégicos para melhoria da experiência do consumidor.

---

* **Autores:**
- Kevin Joel
- Paulo Henrique
- Marcos Gomes
- Vitor de Freitas

