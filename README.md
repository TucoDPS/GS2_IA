# Previsão de Duração de Carregamento de Veículos Elétricos com Inteligência Artificial

## Descrição
Este projeto tem como objetivo o desenvolvimento e treinamento de um modelo de rede neural para prever a duração do carregamento de veículos elétricos (VE). O modelo utiliza variáveis como hora do dia, dia da semana, mês e quantidade de kWh consumidos para prever a duração do carregamento, otimizando o gerenciamento de recursos energéticos e reduzindo custos associados ao consumo de energia.

## Objetivo
- Desenvolver um modelo de inteligência artificial para prever a duração do carregamento de veículos elétricos.
- Melhorar a gestão de estações de carregamento, otimizando os recursos energéticos.

## Tecnologias Utilizadas
- **Python**
- **Pandas**: Manipulação e limpeza de dados.
- **NumPy**: Cálculos numéricos.
- **Scikit-Learn**: Divisão dos dados e normalização.
- **TensorFlow/Keras**: Construção e treinamento da rede neural.
- **Matplotlib**: Visualização de dados e resultados.

## Metodologia
1. **Carregamento e Limpeza dos Dados**: Tratamento de valores ausentes e conversão de formatos.
2. **Feature Engineering**: Extração de variáveis temporais como hora do dia, dia da semana e mês.
3. **Divisão e Normalização dos Dados**: Divisão em conjuntos de treino e teste, seguida de normalização.
4. **Construção e Treinamento da Rede Neural**: Rede neural com 3 camadas ocultas, otimizador Adam e função de perda MSE.
5. **Avaliação do Modelo**: Métricas MAE (erro médio absoluto) e RMSE (raiz do erro quadrático médio).

## Arquitetura da Rede Neural
A rede neural foi composta por:
- **Camada de Entrada**: Recebe as variáveis normalizadas.
- **Camadas Ocultas**:
  - Primeira camada oculta: 64 neurônios com ativação ReLU.
  - Segunda camada oculta: 32 neurônios com ativação ReLU.
  - Terceira camada oculta: 16 neurônios com ativação ReLU.
- **Camada de Saída**: 1 neurônio para prever a duração (regressão).

## Resultados
O modelo foi avaliado com as seguintes métricas:
- **MAE (Erro Médio Absoluto)**: ~7,5 horas.
- **RMSE (Raiz do Erro Quadrático Médio)**: ~11,6 horas.


