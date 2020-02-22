![deep dream](https://b2h3x3f6.stackpathcdn.com/assets/landing/img/gallery/2.jpg)



## Arquiteturas de redes neurais

Neste pequeno artigo, falarei e darei poucos exemplos de diversas arquiteturas de redes neurais, como o perceptron, ADALINE, MADALINE entre outros. Estas se diferenciam pelos cálculos, pela composição estrutural, pela quantidade de neurônios etc., e são usadas em diversas aplicações, dependendo, é claro, da arquitetura. O artigo poderá ter atualizações futuras, como continuações, com explicações mais detalhadas, cálculos matemáticos, exemplos e mais.

### Perceptron

Inventado em 1958, por Frank Rosenblatt no *Cornell Aeronautical Laboratory*, um perceptron é a rede neural artificial feed-forward mais simples possível: um modelo computacional de apenas um neurônio. É um tipo de classificador linear, ou seja, um algoritmo de classificação que faz suas previsões com base em uma função preditora linear combinando um conjunto de pesos com o vetor de recursos. Este modelo pode consistir em uma ou mais entradas (*inputs*), um processador e apenas uma saída. Por ser muito antiga, o seu uso é extremamente limitado.

![Máquina Mark I Perceptron, de Frank Rosenblatt, no Cornell Aeronautical Laboratory, em Nova Iorque](https://assets.bwbx.io/images/users/iqjWHBFdfxIU/itEHc64uxdqM/v0/-1x-1.jpg)
*Máquina "Mark I Perceptron", de Frank Rosenblatt, no Cornell Aeronautical Laboratory, em Nova Iorque, por volta de 1960.*

###  ADALINE

Em 1959, Bernard Widrow e Marcian Hoff, de Stanford, desenvolveram modelos chamados "ADALINE" e "MADALINE". Os nomes vieram de *Multiple ADAptive LINear Elements* (Múltiplos Elementos Lineares Adaptativos, em português). ADALINE foi desenvolvido para reconhecer padrões binários de modo que, se ele, o modelo, estivesse lendo bits de streaming de uma linha telefônica, poderia prever o próximo bit.
A diferença entre ADALINE e o Perceptron é que, na fase de aprendizado, os pesos são ajustados de acordo com a soma ponderada das entradas, já que no Perceptron, a rede é passada para a função de ativação e a saída da função é usada para ajustar os pesos.

### MADALINE

Desenvolvida por Bernard Widrow e Marcian Hoff, em 1959, é similar à ADALINE, porém, é multicamadas e foi a primeira rede neural a ser aplicada em problemas reais: usava um filtro adaptativo para eliminar eco em chamadas de telefone.

### LeNet

Em 1998, Yann LeCun, Leon Bottou, Yosuha Bengio e Patrick Haffner propuseram uma arquitetura de rede neural para reconhecimento de números manuscritos e impressos em máquina, chamada de LeNet-5. A arquitetura é direta e simples de entender, e é por isso que ela é usada principalmente como um primeiro passo para o ensino da Rede Neural da Convolução.

![Arquitetura LeNet-5](https://miro.medium.com/max/1000/1*1TI1aGBZ4dybR6__DI9dzA.png)
*Arquitetura LeNet-5*

A arquitetura LeNet-5 consiste em dois conjuntos de camadas convolucionais e médias de agrupamento, seguidas por uma camada convolucional de achatamento, duas camadas totalmente conectadas e finalmente um classificador softmax.
