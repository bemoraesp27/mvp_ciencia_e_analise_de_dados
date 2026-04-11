# MVP - Ciência e Análise de Dados

Este repositório contém o notebook e a base de dados utilizados no projeto de Análise Exploratória de Dados e Ciência de Dados de acidentes de trânsito.

## 📂 Estrutura
- `Base_acidentes.xlsx` → dataset original
- `mvp_acidentes.ipynb` → notebook com todo o código e análises

## 🎯 Objetivo
Aplicar técnicas de estatística e modelagem preditiva para investigar fatores relacionados à gravidade dos acidentes e testar 3 principais hipóteses:

`Hipótese 1:` Acidentes noturnos (noite e madrugada) tem maior chance de resultar em mortes do que acidentes diurnos (manhã e tarde).

`Hipótese 2:` Acidentes em vias urbanas são mais comuns de resultarem em fatalidades (feridos graves ou mortos) do que em vias rurais.

`Hipótese 3:` Condições de pista ruins como chuva e neve estão diretamente ligadas a uma maior taxa de fatalidade em acidentes.

## 📊 Principais Inisghts

`Hipótese 1:` Acidentes noturnos (noite e madrugada) tem maior chance de resultar em mortes do que acidentes diurnos (manhã e tarde).

**A Hipótese 1 se mostrou verdadeira** visto que se utilizarmos a faixa da manhã, temos:
- 2.86 vezes mais chance de morte na madrugada e 2.42 a noite;

Assim como utilizando a tarde como referência temos:
- 2.08 vezes mais chance de morte na madrugada e 1.77 vezes a noite.

Dessa forma, **nossa hipótese 1 está VALIDADA**.

`Hipótese 2:` Acidentes em vias urbanas são mais comuns de resultarem em fatalidades (feridos graves ou mortos) do que em vias rurais.

**Já na hipótese 2, vemos que ela se mostrou INCORRETA**, pois acidentes rurais tem 1.3 vezes mais chance de ocorrerem em fatalidades do que acidentes em vias urbanas.

`Hipótese 3:` Condições de pista ruins como chuva e neve estão diretamente ligadas a uma maior taxa de fatalidade em acidentes.

Por fim, em nossa **hipótese 3, vemos que ela também se mostrou INCORRETA**, pois vimos que condições ruins geram 30.6% menos de chance de ocorrerem fatalidades do que em condições boas.

Além disso, **a partir da AED vimos a importancia de padronizar nosso dataset em caso da criação de um modelo de predição**, visto a quantidade de outliers e a influência/impacto que eles podem gerar em nosso dataset.

## 🚀 Técnica Utilizadas

Análise de Dados:
- Estatística descritiva
- Distribuição de Atributos
- Tratamento de Valores nulos

Pré Processamento de Dados
- Discretização
- Feature Engineering
- Padronização
 
Teste de Hipóteses
- Teste Qui-quadrado
- Teste de Proporções (z-test)
- Regressão Logística

Link para o notebook no Colab: https://colab.research.google.com/drive/1WElman4Dgb5CHQfi9mvlYZ0iYWsaeR9D?usp=sharing





