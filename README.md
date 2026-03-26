# Análise Estatística e Regressão Linear em Python

## Descrição do Projeto

Este projeto implementa uma análise estatística completa entre dois conjuntos de dados utilizando Python.

O sistema calcula:

* Coeficiente de correlação de Pearson
* Coeficiente de determinação (R²)
* Equação da reta de regressão linear

Além disso, gera uma tabela organizada dos dados e um gráfico de dispersão com a reta de regressão.

O objetivo é aplicar conceitos de estatística, álgebra e visualização de dados.

---

## Tecnologias Utilizadas

* Python
* NumPy (cálculos numéricos)
* Pandas (manipulação de dados)
* Matplotlib (visualização gráfica)

---

## Funcionalidades

* Entrada de dados X e Y pelo usuário
* Cálculo do coeficiente de correlação de Pearson
* Cálculo do coeficiente de determinação (R²)
* Geração da equação da reta de regressão
* Exibição de tabela com os dados
* Plotagem de gráfico de dispersão com regressão

---

## Funcionamento

1. O usuário insere os valores de X e Y separados por vírgula
2. O programa verifica se os dados são válidos
3. Calcula:

   * Somatórios (ΣX, ΣY, ΣXY, etc.)
   * Correlação de Pearson
   * Coeficiente de determinação
   * Reta de regressão
4. Exibe os resultados no terminal
5. Gera um gráfico com os dados e a reta de regressão

---

## Exemplos de Execução

### Entrada:

X: 1,2,3,4
Y: 2,4,6,8

### Saída:

Correlação de Pearson: 1.0
Coeficiente de determinação: 100%
Equação da reta: y = 2.00x + 0.00

---

## Observações Importantes

* Os valores de X e Y devem ter o mesmo tamanho
* O coeficiente de Pearson varia entre -1 e 1
* O valor de R² indica o nível de ajuste da regressão
* O gráfico facilita a visualização da relação entre as variáveis
* O programa utiliza arredondamento baseado na entrada do usuário

---

## Conceitos Praticados

* Estatística (Correlação e Regressão)
* Álgebra Linear
* Manipulação de dados
* Visualização com gráficos
* Programação em Python
