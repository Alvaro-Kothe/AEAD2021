# Trabalho final de Aprendizagem estatística em altas dimensões

Trabalho final da disciplina aprendizagem estatística em altas dimensões,
ministrada no segundo semestre de 2021 pela professora Florencia Leonardi na
Universidade de São Paulo.

## Descrição do trabalho

> O trabalho final da disciplina consistirá numa análise de dois conjuntos de dados e na entrega de um relatório. As instruções para a análise de cada conjunto de dados estão nos arquivos correspondentes. A proposta é que para cada um dos conjuntos, vocês implementem as abordagens estudadas no curso e selecionem a mais apropriada para cada problema. Junto com o relatório final, vocês deverão submeter uma tabela com predições do modelo selecionado numa amostra de teste e os códigos utilizados num arquivo R Markdown documentado.  
>
> A escolha do modelo é de inteira responsabilidade do aluno(a), utilizando técnicas vistas no curso para seleção de modelos e/ou variáveis. Dentre os modelos considerados não poderão faltar:
>
> 1- Modelos lineares com regularização
>
> 2- Modelos baseados em árvores (bagging, florestas aleatórias ou boosting)
>
> 3- Redes neurais
>
> Vocês poderão também propor ou comparar estas abordagens com outras, desde que estejam descritas no relatório. O objetivo do trabalho é obter um bom preditor para os dados de teste, que serão disponibilizados posteriormente.

## Código e relatório final

O código para gerar o [relatório](relatorio/relatorio.pdf) se encontra na
pasta [relatorio](relatorio/).

Neste trabalho foram ajustados modelos de

- Lasso
- Ridge
- XGBoost
- Random Forest
- Rede neural com tensorflow.

Para realizar a seleção de hiper-parâmetros foi utilizado validação cruzada.
