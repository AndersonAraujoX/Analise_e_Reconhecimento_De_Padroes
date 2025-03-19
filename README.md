# Projetos de Reconhecimento de Padrões

Este repositório contém os projetos desenvolvidos para a disciplina de Reconhecimento de Padrões. Os projetos exploram diversos conceitos e técnicas na área, desde análise de sinais e autómatos até redes neurais e PCA.

## Projeto 1: Análise e Modelagem de Sinais

Este projeto envolve a análise de sinais unidimensionais e a criação de modelos para geração de padrões semelhantes.

* **Análise de sinais:** Leitura e visualização de arquivos contendo sinais, incluindo visualizações como sequências de valores e histogramas.
* **Estatísticas e agrupamentos:** Obtenção de estatísticas dos sinais, identificação de grupos e proposição de modelos para gerar novos padrões com características semelhantes aos originais.
* **Comparação de sinais:** Comparação de visualizações e estatísticas dos sinais originais e dos sinais gerados pelos modelos.
* **Visualização como imagens:** Visualização dos sinais modelados como imagens em níveis de cinza.
* **Implementação de autômatos:** Implementação de programas para gerar visualizações com autômatos e combinar autômatos para obter resultados específicos. 

## Projeto 2: Classificação com k-Vizinhos

Este projeto explora a aplicação do algoritmo k-vizinhos para classificação utilizando o conjunto de dados Iris.

* **Visualização dos dados Iris:** Visualização dos grupos em todas as combinações de 2 entre os 4 atributos, com uso de cores e legendas em scatterplots.
* **Classificação k-vizinhos:** Aplicação do algoritmo k-vizinhos nas configurações 2-a-2, com divisão dos dados para treinamento e teste.
* **Avaliação de desempenho:** Obtenção, apresentação e discussão do desempenho para cada configuração de atributos, utilizando matrizes de confusão.
* 
## Projeto 3: Autómatos Geradores de Sinais

Este projeto foca na implementação de autómatos para geração de sinais 1D.

* **Implementação de autômatos:** Implementação de três autômatos geradores de sinais 1D, incluindo o autômato do CDT-23, e outros dois para gerar sinais de onda retangular e triangular.
* **Geração de sinais:** Geração de 50 realizações de cada um dos 3 tipos de sinais, totalizando 150 objetos.
* **Extração e visualização de medidas:** Extração de medidas dos sinais e visualização em scatterplots para identificar casos que contribuem para a separação das categorias.

## Projeto 4: Transformação e Normalização de Atributos

Este projeto visa a reprodução de resultados relacionados à transformação e normalização de atributos.

* **Reprodução de resultados:** Reprodução dos resultados do CDT-24, incluindo figuras específicas.
* **Implementação de transformações:** Proposição e implementação de transformações para obter resultados semelhantes quando a transformação usada não estiver indicada. 

## Projeto 5: Análise de Componentes Principais (PCA)

Este projeto explora a aplicação de PCA para visualização e classificação de dados.

* **PCA nos dados Iris:** Realização de PCA nos dados Iris, considerando as 4 medidas originais, e visualização dos grupos.
* **Classificação com k-vizinhos e PCA:** Realização de classificação supervisionada por k-vizinhos, utilizando metade dos dados para treinamento e metade para teste, e obtenção das matrizes de confusão.
* **Comparação com projeto anterior:** Comparação dos resultados com um projeto anterior que não utilizava PCA.
* **PCA em dados gerados por autômatos:** Repetição do procedimento para dados gerados por autômatos probabilísticos.
* **Efeito da estandardização:** Verificação do efeito de estandardizar ou não os dados.
* **Variância explicada:** Identificação da explicação da variância com um e dois eixos do PCA.
* **Implementação de rotinas:** Implementação de rotinas para autovalores/autovetores, cálculo de matrizes de covariância, manipulação de dados/resultados, estandardização, construção de matrizes de confusão e k-vizinhos utilizando comandos básicos da linguagem. 

## Projeto 6: Redes Neurais para Reconhecimento de Padrões

Este projeto aborda a implementação de redes neurais para reconhecimento de padrões.

* **Neurônios como discriminadores lineares:** Obtenção de resultados análogos aos de um discriminador linear, reproduzindo figuras específicas e obtendo configurações de parâmetros para separar entre diferentes categorias.
* **Rede convolutiva para reconhecimento de dígitos:** Implementação de uma rede convolutiva supervisionada para reconhecer números manuscritos da base MNIST.
    * Escolha de protótipos ou uso da média dos caracteres como vetor de peso.
    * Obtenção de matrizes de confusão com e sem sigmoide e comparação dos resultados.
* **(Opcional) Mapa Auto-Organizável (SOM):** Implementação do SOM (rede de Kohonen, não-supervisionada) utilizando dados de caracteres manuscritos e obtenção de matrizes de confusão para caracterizar o desempenho. 
